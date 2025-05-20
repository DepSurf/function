# Function: <code>PageLocked</code>

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
In mm/filemap.c (ffffffff8118cbd9)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_read
  - mm/filemap.c:filemap_fault
```
```
In mm/page-writeback.c (ffffffff81198c9d)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8119dce5)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff811a0225)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811a8415)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff811bdb06)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811c30f5)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:munlock_vma_page
```
```
In mm/rmap.c (ffffffff811cb24e)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:hugepage_add_anon_rmap
```
```
In mm/swapfile.c (ffffffff811d55df)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/frontswap.c (ffffffff811d7655)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/hugetlb.c (ffffffff811dee53)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff811f0cf8)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:pmd_trans_migrating
```
```
In mm/huge_memory.c (ffffffff811f4c89)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In fs/buffer.c (ffffffff81242fcc)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__block_write_begin
```
```
In fs/proc/task_mmu.c (ffffffff812781b3)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inode.c (ffffffff81296059)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8129fe15)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff812d6aee)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff812e0465)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/crypto.c (ffffffff812e53f5)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypt
  - fs/ext4/crypto.c:ext4_decrypt
```
```
In fs/jbd2/transaction.c (ffffffff812e8195)
Location: include/linux/page-flags.h:209
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In mm/filemap.c (ffffffff811a13d6)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811af558)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811b3365)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff811b7335)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811c35c5)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff811d90a8)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811def13)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/rmap.c (ffffffff811e9575)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff811f35da)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811fd344)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81212d95)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81216297)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8121bfde)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/buffer.c (ffffffff8126c8f9)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidatepage
```
```
In fs/crypto/crypto.c (ffffffff81288c65)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/proc/task_mmu.c (ffffffff812a5047)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/ext4/inode.c (ffffffff812c364a)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce705)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff813067d9)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81310135)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/jbd2/transaction.c (ffffffff81316d55)
Location: include/linux/page-flags.h:255
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff811b1013)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811bfc18)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811c39e5)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff811c7945)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811d3635)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff811e853b)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811eed33)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff811f6c8f)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff811fa8c5)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff81204092)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8120de13)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81225100)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228843)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8122d794)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/buffer.c (ffffffff8127f959)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff8129d7a5)
Location: include/linux/page-flags.h:264
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ba9a6)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/ext4/inode.c (ffffffff812d8aea)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e44e5)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/move_extent.c (ffffffff8131c799)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81325f25)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/jbd2/transaction.c (ffffffff8132cd45)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff811b8470)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811c7de8)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811cbdf5)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff811d0085)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811dbe35)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff811f7a35)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811f9ce3)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff81201b72)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81205565)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8120f735)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81219c30)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81230820)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81231ec6)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8123a07c)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/buffer.c (ffffffff8128d159)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff812ac525)
Location: include/linux/page-flags.h:264
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c86f2)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/ext4/inline.c (ffffffff812f9d45)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff812fcdc5)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81315318)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e1c5)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81341f25)
Location: include/linux/page-flags.h:264
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff811ca805)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff811dcc28)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff811e0de5)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff811e5536)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811f1ce6)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8120a987)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff81212133)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff8121ad36)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121e515)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8122afa3)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81234c8f)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff8124b722)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812559df)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8125873c)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/buffer.c (ffffffff812af979)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff812cfdd3)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/proc/task_mmu.c (ffffffff812ec550)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8131e375)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813216c5)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81339b15)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813427e6)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81366566)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff811edcd7)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff811fdcc5)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81202675)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81206b05)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff812107c5)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8122b813)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/mlock.c (ffffffff81232e73)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff8123cb65)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812403e0)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8124c229)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81257bc2)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff8126e3e7)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81279894)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8127d14a)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In fs/buffer.c (ffffffff812d77fd)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff812fa693)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/proc/task_mmu.c (ffffffff81319b8e)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8134c5a5)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8134f725)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813680e2)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81370655)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81394c05)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff811ff290)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81210955)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81214ff5)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81219685)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81223875)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8123ebdb)
Location: include/linux/page-flags.h:281
Inline: True
```
```
In mm/mlock.c (ffffffff81246643)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff8125103b)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81254ae0)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff8126072c)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8126c27b)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81283275)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128deca)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff81291cc3)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/buffer.c (ffffffff812ecc5d)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff8130fa13)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_page
```
```
In fs/proc/task_mmu.c (ffffffff81330c67)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff813646e5)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81367905)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81380564)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388ae5)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813ad975)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff812162f2)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81220096)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81224a15)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81229175)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81232d65)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff81250959)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/mlock.c (ffffffff8125889d)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff81263327)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81266da0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81287639)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812a0ed5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a884b)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812abf44)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff8130e40f)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81336f85)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/proc/task_mmu.c (ffffffff81358a88)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8138cfd5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81390c05)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813a93e8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2bd5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813d7cb5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff81223c02)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff8122db46)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff812327a5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81237025)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81240f85)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8125ef09)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/mlock.c (ffffffff81266d6d)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff81271ad7)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812756c0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81297249)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812ae9d4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b9dcb)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812bd754)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff8132142f)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff8134ab65)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff813511ae)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffffffff81370cd8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff813a5a35)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a95c5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813c2308)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cbc35)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813f1d85)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff8124e2b5)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff8125a10e)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8125faaf)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81263eb5)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8126f8f5)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8128fb83)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/mlock.c (ffffffff81296fa2)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff812a20ff)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a6ab0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean
```
```
In mm/hugetlb.c (ffffffff812ca84f)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812e4111)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ee97a)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812f2e9a)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff8135bb72)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/crypto/crypto.c (ffffffff813902d5)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff81397bf3)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff813ab7da)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/proc/task_mmu.c (ffffffff813b8777)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/ext4/inline.c (ffffffff813f1cc3)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813f5465)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff8140e9cf)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81417d95)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8143f395)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff812586c5)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__wait_on_page_locked_async
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff81264290)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8126a085)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8126e925)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81279405)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8129a448)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff812a1fc5)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff812ada44)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b1f50)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean
```
```
In mm/hugetlb.c (ffffffff812d647f)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812f0146)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812f9fea)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812fd4dc)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff8136a112)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/crypto/crypto.c (ffffffff813a1924)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff813a9473)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff813bc1b4)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/proc/task_mmu.c (ffffffff813ca1a7)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/ext4/inline.c (ffffffff814044b3)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81407c05)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81421f18)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8142b8a2)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff8145b604)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff8125cd45)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff81269e70)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8126f195)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81273a55)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8127e605)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8129f64b)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff812a7855)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff812b2ec5)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b7620)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean
```
```
In mm/hugetlb.c (ffffffff812dd629)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812f5823)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81300d96)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff8130423b)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff81370d32)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/crypto/crypto.c (ffffffff813a8ac4)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff813b09b3)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff813c3692)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/proc/task_mmu.c (ffffffff813d0d89)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/ext4/inline.c (ffffffff8140aa95)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8140e085)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff814285d8)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff814324c0)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff81460f44)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff81298cb5)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:filemap_range_needs_writeback
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff812a6b00)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff812ac315)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff812b2b05)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff812bc143)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff812e0af0)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff812e8e35)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff812f4a68)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f9d30)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean
```
```
In mm/hugetlb.c (ffffffff813247cd)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff81342907)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813457ce)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134df6e)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In fs/buffer.c (ffffffff813bf982)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff813f824d)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff8140059a)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/iomap/buffered-io.c (ffffffff81413cfa)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/proc/task_mmu.c (ffffffff81422615)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/ext4/inline.c (ffffffff8145d6e5)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81460f55)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff8147c318)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81485d80)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff814b6424)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff812f5b8b)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:filemap_range_has_writeback
```
```
In mm/shmem.c (ffffffff8131b981)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff81341368)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff81354107)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135ffd0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff813910d4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate_device.c (0)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bb93f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c71b4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:492
Inline: True
```
```
In fs/buffer.c (ffffffff814455d5)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff8146af31)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff81474535)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffffffff8149b83c)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/ext4/inline.c (ffffffff814dc047)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814e17f9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff814fea88)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81509338)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In mm/filemap.c (ffffffff8135fb3c)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff813b9085)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff813ce6c6)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813daf2d)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff813fd6e8)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff814128ef)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff81421b73)
Location: include/linux/page-flags.h:471
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/page-flags.h:471
Inline: True
```
```
In mm/huge_memory.c (ffffffff8144046b)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144b066)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:471
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:471
Inline: True
```
```
In fs/buffer.c (ffffffff814d4e65)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:grow_dev_page
```
```
In fs/crypto/crypto.c (ffffffff814fc0a1)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff81506759)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffffffff8152fd20)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/ext4/inline.c (ffffffff81574fe7)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8157ab19)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff815992d8)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a3f15)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In mm/filemap.c (ffffffff81390b04)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff813e95cb)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mprotect.c (ffffffff81402ef9)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8140e0af)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff814309e2)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445f0b)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff814568b0)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (0)
Location: include/linux/page-flags.h:465
Inline: True
```
```
In mm/huge_memory.c (ffffffff814760eb)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147ed7d)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:465
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:465
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff81533303)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/proc/task_mmu.c (ffffffff81567c33)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/filemap.c (ffffffff813ba781)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff8141450b)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mprotect.c (ffffffff8142f4c3)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8143a7ff)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff814691b5)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147f915)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff814913a6)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (0)
Location: include/linux/page-flags.h:467
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a59a7)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (0)
Location: include/linux/page-flags.h:467
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/page-flags.h:467
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff815681fb)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/proc/task_mmu.c (ffffffff815a00a4)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/filemap.c (ffff8000102b1610)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffff8000102bc9d8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffff8000102c2588)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffff8000102c8020)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffff8000102d2a90)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffff8000102f7074)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffff8000102fdf74)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/rmap.c (ffff80001030b664)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffff80001033508c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffff800010352ae8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffff800010356074)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffff80001035ec4c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffff8000103d87ac)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffff80001040b404)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffff800010413218)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffff800010439780)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffff800010478f34)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffff80001047d440)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffff800010499d28)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a3de8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffff8000104cc270)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (c04ddfa0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (c04e8f58)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (c04ed7dc)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (c04f1f74)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c04fb590)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (c0519180)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (c051d164)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/rmap.c (c052675c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (c0552478)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/buffer.c (c05b31ec)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_slow
```
```
In fs/crypto/crypto.c (c05d8618)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (c05df500)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (c06013dc)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/ext4/inline.c (c063afa8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c063ed14)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c065b528)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0665c78)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (c068febc)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (c000000000362f70)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:try_to_release_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache
```
```
In mm/page-writeback.c (c000000000375410)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (c00000000037c540)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (c000000000383384)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c0000000003921ac)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (c0000000003bf194)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (c0000000003c95e0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (c0000000003d60ec)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003db7d8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean
```
```
In mm/hugetlb.c (c00000000040e768)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (c000000000434cf4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (c0000000004441bc)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (c000000000448088)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (c0000000004dea80)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (c000000000517f9c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (c000000000521000)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (c00000000054cb5c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (c00000000059c4c4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c0000000005a107c)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c0000000005c3fa0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d0ed0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (c000000000605bf0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffe0001d6d1a)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffe0001df980)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffe0001e39b4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffe0001e7552)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffe0001ee6ba)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffe00020788a)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffe00020c5ec)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/rmap.c (ffffffe000214fc8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffe000231860)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffe00023f752)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/buffer.c (ffffffe000292e4e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffe0002b505a)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffe0002bada0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffffffe0002d36b8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffe0003046e8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffe000306ee2)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffe00031d4f4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe000325340)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffe000344e10)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff8121c252)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81226196)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8122adf5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8122f675)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff812395d5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff81257559)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/mlock.c (ffffffff8125f3bd)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff8126a127)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126dd10)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128f829)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812a6fb4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b23ab)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812b5d34)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff81319a0f)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81343145)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff8134978e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffffffff813692b8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8139e015)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a1ba5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813ba8e8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c4215)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813ea365)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff8120f442)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81219326)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff8121df15)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81222735)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8122c615)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff8124a573)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812517dd)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff8125c311)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125fd40)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812814f2)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812989f0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a373b)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812a6eee)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff8130a5cf)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81333e25)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff8133a46e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffffffff81359563)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8138eaa5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81392635)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813ab378)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b4c95)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813dade5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff81219ff2)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff81223f36)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81228b95)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8122d415)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81237375)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff812552f9)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/mlock.c (ffffffff8125d15d)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff81267ec7)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126bab0)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128d639)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812a4dc4)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b01bb)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812b3b44)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff813174df)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81340c15)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff8134725e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffffffff81366d88)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/ext4/inline.c (ffffffff8139b875)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8139f405)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813b8148)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c16a5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813e76e5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff812290e2)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/page-writeback.c (ffffffff812331f6)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:write_one_page
```
```
In mm/swap.c (ffffffff81237f15)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8123c815)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff812468a5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/memory.c (ffffffff81264dad)
Location: include/linux/page-flags.h:312
Inline: True
```
```
In mm/mlock.c (ffffffff8126cb52)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_vma_mapped.c (ffffffff81277849)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8127b440)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8129d3cf)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/migrate.c (ffffffff812b5920)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_trans_migrating
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812c04fb)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/khugepaged.c (ffffffff812c3f85)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/buffer.c (ffffffff813290cf)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
```
```
In fs/crypto/crypto.c (ffffffff81353f15)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
  - fs/crypto/crypto.c:fscrypt_encrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff8135a55e)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/proc/task_mmu.c (ffffffff8137a3d8)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/ext4/inline.c (ffffffff813afd35)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813b3aa5)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813cce48)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d6805)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/jbd2/transaction.c (ffffffff813fce95)
Location: include/linux/page-flags.h:312
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
</details>
</li>
</ul>

## Differences
