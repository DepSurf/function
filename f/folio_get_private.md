# Function: <code>folio_get_private</code>

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
In mm/migrate.c (ffffffff813b2a4f)
Location: include/linux/mm_types.h:335
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_mapping
```
```
In fs/buffer.c (ffffffff81446b49)
Location: include/linux/mm_types.h:335
Inline: True
Inline callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_dirty_folio
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/iomap/buffered-io.c (ffffffff8148857b)
Location: include/linux/mm_types.h:335
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_migrate_page
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/inode.c (ffffffff814dfc77)
Location: include/linux/mm_types.h:335
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
```
```
In fs/jbd2/transaction.c (ffffffff8153fd64)
Location: include/linux/mm_types.h:335
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/mm_types.h:335
Inline: True
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
In mm/hugetlb.c (0)
Location: include/linux/mm_types.h:472
Inline: True
```
```
In mm/migrate.c (ffffffff814341e5)
Location: include/linux/mm_types.h:472
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In fs/buffer.c (ffffffff814d2c15)
Location: include/linux/mm_types.h:472
Inline: True
Inline callers:
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_dirty_folio
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff814d9a44)
Location: include/linux/mm_types.h:472
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8151c3f1)
Location: include/linux/mm_types.h:472
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/inode.c (ffffffff81578fb7)
Location: include/linux/mm_types.h:472
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
```
```
In fs/ext4/move_extent.c (ffffffff81599cf5)
Location: include/linux/mm_types.h:472
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff815de8e4)
Location: include/linux/mm_types.h:472
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/mm_types.h:472
Inline: True
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
In mm/hugetlb.c (0)
Location: include/linux/mm_types.h:417
Inline: True
```
```
In mm/migrate.c (ffffffff81469b25)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In fs/buffer.c (ffffffff8150c188)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:folio_init_buffers
  - fs/buffer.c:block_dirty_folio
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8150e9d7)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff815545fe)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_is_partially_uptodate
  - fs/iomap/buffered-io.c:iomap_read_inline_data
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
  - fs/iomap/buffered-io.c:iomap_page_create
```
```
In fs/ext4/inline.c (ffffffff815ad2bb)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815bc771)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:mpage_process_folio
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff815cfd45)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815da9fb)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db6b8)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff815f5b68)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff81616344)
Location: include/linux/mm_types.h:417
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/mm_types.h:417
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
In mm/hugetlb.c (0)
Location: include/linux/mm_types.h:495
Inline: True
```
```
In mm/migrate.c (ffffffff81498ab5)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:folio_migrate_mapping
```
```
In fs/buffer.c (ffffffff81540d85)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:folio_zero_new_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:folio_init_buffers
  - fs/buffer.c:block_dirty_folio
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff815432f1)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8158af55)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:ifs_free
```
```
In fs/ext4/inline.c (ffffffff815e606b)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff815f5550)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_dirty_folio
  - fs/ext4/inode.c:ext4_journalled_dirty_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_journal_folio_buffers
  - fs/ext4/inode.c:mpage_process_folio
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff816085c2)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff816131bb)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613f85)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff8162e478)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff8164f164)
Location: include/linux/mm_types.h:495
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/mm_types.h:495
Inline: True
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
