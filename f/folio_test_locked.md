# Function: <code>folio_test_locked</code>

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
In mm/filemap.c (ffffffff812ef465)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/filemap.c:filemap_release_folio
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/page-writeback.c (ffffffff812fdb8d)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_write_one
```
```
In mm/swap.c (ffffffff813064a5)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff8130cc55)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8135bea7)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/rmap.c:folio_mkclean
```
```
In mm/hugetlb.c (ffffffff81392cab)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff813e28c9)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/buffer.c (ffffffff814438db)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/iomap/buffered-io.c (ffffffff8148995e)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/inode.c (ffffffff814dfc65)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/jbd2/transaction.c (ffffffff8153fd54)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff81359fa5)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/filemap.c:filemap_release_folio
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/page-writeback.c (ffffffff81368368)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_write_one
```
```
In mm/swap.c (ffffffff81370545)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff81381198)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8138f57f)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/shmem.c:shmem_writepage
```
```
In mm/rmap.c (ffffffff813d6b27)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/rmap.c:folio_mkclean
```
```
In mm/hugetlb.c (ffffffff814116f6)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff81469e29)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/buffer.c (ffffffff814d213b)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/iomap/buffered-io.c (ffffffff8151d7fe)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/inode.c (ffffffff81578fa5)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
```
```
In fs/jbd2/transaction.c (ffffffff815de8d4)
Location: include/linux/page-flags.h:471
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff8138b9e5)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/filemap.c:filemap_release_folio
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/swap.c (ffffffff813a26c5)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff813b254a)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff8140f682)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:folio_mkclean
```
```
In mm/hugetlb.c (ffffffff814449b2)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/zsmalloc.c (ffffffff8149f029)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/buffer.c (ffffffff81509b4b)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/crypto/crypto.c (ffffffff81533514)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff8153e537)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff81555a9f)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/inline.c (ffffffff815acd0e)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815b03d5)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff815cfcf8)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815da985)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/jbd2/transaction.c (ffffffff81616334)
Location: include/linux/page-flags.h:465
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
In mm/filemap.c (ffffffff813b54d7)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/filemap.c:filemap_release_folio
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:filemap_read_folio
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:filemap_range_has_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/swap.c (ffffffff813cc345)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/vmscan.c (ffffffff813dbaed)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:__remove_mapping
```
```
In mm/rmap.c (ffffffff814381c7)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/rmap.c:folio_mkclean
```
```
In mm/hugetlb.c (ffffffff8147ebcc)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/khugepaged.c (ffffffff814afa42)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/zsmalloc.c (ffffffff814ce789)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - mm/zsmalloc.c:lock_zspage
  - mm/zsmalloc.c:lock_zspage
```
```
In fs/buffer.c (ffffffff8153e97b)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/buffer.c:try_to_free_buffers
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/crypto/crypto.c (ffffffff81568478)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_pagecache_blocks
```
```
In fs/verity/verify.c (ffffffff81573ad7)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_data_blocks
```
```
In fs/iomap/buffered-io.c (ffffffff8158bd57)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_writepage_map
```
```
In fs/ext4/inline.c (ffffffff815e59c0)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815e91c5)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81608578)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81613145)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/jbd2/transaction.c (ffffffff8164f154)
Location: include/linux/page-flags.h:467
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
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
