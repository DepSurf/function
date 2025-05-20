# Function: <code>PagePrivate</code>

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
In arch/x86/events/intel/bts.c (ffffffff8100d1e3)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff8101452d)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff8119a9f0)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/page-writeback.c:__set_page_dirty_nobuffers
```
```
In mm/compaction.c (ffffffff811b601e)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/hugetlb.c (ffffffff811db813)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/migrate.c (ffffffff811f21d3)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:buffer_migrate_page
```
```
In mm/zsmalloc.c (ffffffff81204fa5)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/zsmalloc.c:free_zspage
  - mm/zsmalloc.c:fix_fullness_group
  - mm/zsmalloc.c:fix_fullness_group
  - mm/zsmalloc.c:fix_fullness_group
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
  - mm/zsmalloc.c:zs_unmap_object
```
```
In mm/balloon_compaction.c (ffffffff8120738c)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_dequeue
  - mm/balloon_compaction.c:balloon_page_isolate
```
```
In fs/buffer.c (ffffffff81242932)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_begin
```
```
In fs/mpage.c (ffffffff8124d6e5)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/file.c (ffffffff812924aa)
Location: include/linux/page-flags.h:233
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8129677e)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
```
```
In fs/ext4/page-io.c (ffffffff8129f6fd)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/super.c (ffffffff812ac9b9)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/ext4/move_extent.c (ffffffff812d6b3a)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff812e0d6e)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/readpage.c (ffffffff812e2f75)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff812e81a0)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/hugetlbfs/inode.c (ffffffff812f38b9)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c3871)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
```
```
In drivers/xen/grant-table.c (ffffffff814c559b)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/bitmap.c (ffffffff8169c1d5)
Location: include/linux/page-flags.h:233
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100d3ad)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81013f8d)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff811af30a)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fe146)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff81211085)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8126c7f5)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff81275f43)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/file.c (ffffffff812bfa76)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cda51)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812ce779)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/super.c (ffffffff812e1079)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/ext4/move_extent.c (ffffffff81306834)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81310afc)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/readpage.c (ffffffff81312e63)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff81316d81)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In fs/hugetlbfs/inode.c (ffffffff81327d6f)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
```
In drivers/xen/grant-table.c (ffffffff81515c0b)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/bitmap.c (ffffffff816fe7d9)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100d46a)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff8101410e)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff811bf9aa)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120ec16)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff81223245)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8127f855)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81289c2d)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/file.c (ffffffff812d4c86)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e3821)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e4559)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/super.c (ffffffff812f6ba9)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/ext4/move_extent.c (ffffffff8131c7f4)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/inline.c (ffffffff81326970)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/readpage.c (ffffffff81328e07)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/jbd2/transaction.c (ffffffff8132cd71)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff8154208b)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/bitmap.c (ffffffff81730436)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100d2ea)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81012733)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff811c7b7a)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In mm/hugetlb.c (ffffffff8121a4c6)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff8122ec95)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In fs/buffer.c (ffffffff812903a1)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81296927)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/file.c (ffffffff812f1596)
Location: include/linux/page-flags.h:296
Inline: True
```
```
In fs/ext4/inline.c (ffffffff812fa91e)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff813079a5)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81315372)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff8131e239)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8131e8ee)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff8132b49d)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff81341f51)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81555e7b)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/bitmap.c (ffffffff817482b6)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100d88a)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff810127f9)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff811dc9ba)
Location: include/linux/page-flags.h:297
Inline: True
```
```
In mm/hugetlb.c (ffffffff81235636)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff8124ae0f)
Location: include/linux/page-flags.h:297
Inline: True
```
```
In fs/buffer.c (ffffffff812b30f6)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812b9b87)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8131ef59)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8132c5f5)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81339b7e)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81342859)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81342f15)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff8134f901)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff81366581)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff815b9adb)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/md-bitmap.c (ffffffff817ba546)
Location: include/linux/page-flags.h:297
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100e036)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff810131b7)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff811fca5b)
Location: include/linux/page-flags.h:304
Inline: True
```
```
In mm/hugetlb.c (ffffffff81258576)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff8126ecc5)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff812d9e22)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812e26f4)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8134d176)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff8135abc7)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813681a0)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff813706d9)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81370dc3)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff8137dd71)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff81394c31)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff815f196b)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
```
```
In drivers/md/md-bitmap.c (ffffffff818024c9)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100e506)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81013b87)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff8120f5ab)
Location: include/linux/page-flags.h:316
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126cc48)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff81282925)
Location: include/linux/page-flags.h:316
Inline: True
```
```
In fs/buffer.c (ffffffff812ef310)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff812f7360)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff81365299)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
```
In fs/ext4/inode.c (ffffffff81372e87)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81380623)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffff81388b6a)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81389265)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81396621)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff813ad9a1)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff8160c594)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff8182e7b9)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100edcc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff8101505d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff812215ac)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff81288078)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:free_huge_page
```
```
In mm/migrate.c (ffffffff8129eab5)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/buffer.c (ffffffff81310b60)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8131798f)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8138d948)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139c2db)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813a9d72)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b2c59)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b342f)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff813c0629)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff813d7cec)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81641758)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff81870cb9)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100ee85)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:buf_nr_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81015962)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff8122f05c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297c78)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffff812ae355)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/buffer.c (ffffffff81321315)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8132a80f)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff813a63a8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813b4deb)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813c2ca2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813cbcc7)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813cc5ff)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff813d98dd)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff813f1dbc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff816628f8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff818a2aa9)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff81010363)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff8101756a)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff8125c0f4)
Location: include/linux/page-flags.h:357
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cb338)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffff812e6db5)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8135ba45)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:buffer_check_dirty_writeback
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff813644ca)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813abf52)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/ext4/inline.c (ffffffff813f2bea)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81400280)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff8140ea71)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81417e27)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8141877a)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81425c8d)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff8143f3ca)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81711de3)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff81973d32)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100f8c3)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81017a07)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff812664c4)
Location: include/linux/page-flags.h:366
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d6f71)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffff812f2105)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff81369ff5)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:buffer_check_dirty_writeback
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff813714cc)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813bdda8)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/ext4/inline.c (ffffffff8140533a)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81412a7c)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_should_update_i_disksize
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff81421fab)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8142b92c)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8142c2bd)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff8143d37d)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff8145b62a)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81730020)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff81978c32)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff81010912)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81018d8e)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff8126affc)
Location: include/linux/page-flags.h:366
Inline: True
```
```
In mm/migrate.c (ffffffff812f8455)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8137124d)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:page_zero_new_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:buffer_check_dirty_writeback
  - fs/buffer.c:buffer_check_dirty_writeback
```
```
In fs/mpage.c (ffffffff8137879c)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff813c4f68)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/ext4/inline.c (ffffffff8140b678)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81418edc)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff8142866f)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff8143254c)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81432fb4)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff814431bd)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff81460f6a)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81713a6f)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff8195c122)
Location: include/linux/page-flags.h:366
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff810115e6)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a669)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff812a7f40)
Location: include/linux/page-flags.h:380
Inline: True
```
```
In mm/migrate.c (ffffffff81342ac5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff813bfb69)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff813c5099)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/iomap/buffered-io.c (ffffffff8141499c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/ext4/inline.c (ffffffff8145e2fb)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8146c110)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff8147c3a3)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff81485e0c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81486909)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81496b85)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In fs/jbd2/transaction.c (ffffffff814b644a)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81790481)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff81a01932)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff81012cd1)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff8101cb61)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/migrate.c (ffffffff813b2855)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffff814467f9)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff8144c00c)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff814dc80d)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff814ec110)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff814feb7b)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815093dd)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff8150a107)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff81521ab5)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In drivers/xen/grant-table.c (ffffffff818c892f)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff81b68e07)
Location: include/linux/page-flags.h:530
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff81016d01)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81020f12)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In fs/buffer.c (ffffffff814d5909)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:grow_dev_page
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
  - fs/buffer.c:__find_get_block_slow
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/mpage.c (ffffffff814da4ac)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:clean_page_buffers
```
```
In fs/ext4/inline.c (ffffffff815757ed)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff81585e7a)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff815993cb)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff815a3f96)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815a4d2f)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff815bedc5)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_journalled_writepage_callback
```
```
In drivers/xen/grant-table.c (ffffffff81a1938f)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff81d04937)
Location: include/linux/page-flags.h:509
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff810166e4)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81020c62)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In fs/mpage.c (ffffffff8150efdc)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:clean_page_buffers
  - fs/mpage.c:clean_page_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81a626ff)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff81d6da17)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8101c224)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81026d83)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In drivers/xen/grant-table.c (ffffffff81ab4f2f)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
```
In drivers/md/md-bitmap.c (ffffffff81e24e47)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:write_file_page
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
In mm/page-writeback.c (ffff8000102be37c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffff800010335fc8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffff8000103501ac)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffff8000103dceb0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffff8000103e5fec)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffff80001047997c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffff800010489580)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffff80001049a5b0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffff8000104a3e58)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffff8000104a4a30)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffff8000104ad0bc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffff8000104cc288)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffff80001082cac0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffff800010af850c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In mm/page-writeback.c (c04ea5e4)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/migrate.c (c05518b4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (c05b63b4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (c05bdb30)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (c063b544)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c064ba98)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c065bef4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0665cfc)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c06665f8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (c06757a4)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (c068fee8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/md/md-bitmap.c (c0bd85ac)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In mm/page-writeback.c (c000000000377258)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (c0000000004107d0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (c000000000433e90)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/buffer.c (c0000000004de8a0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (c0000000004ec16c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (c00000000059c994)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c0000000005b05c8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (c0000000005c4d0c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (c0000000005d0f54)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (c0000000005d1b2c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (c0000000005e5520)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (c000000000605c0c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/md/md-bitmap.c (c000000000be4fe0)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
  - drivers/md/md-bitmap.c:write_page
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
In mm/page-writeback.c (ffffffe0001e0dc4)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffe00023211c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffe00023ee88)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffe00029509c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:create_page_buffers
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffe00029b3da)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffe0003049f2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffe000310d32)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffe00031dc78)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffe0003253a8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffe000325b76)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffe0003303fa)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffe000344e26)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/md/md-bitmap.c (ffffffe0006e960e)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100ee85)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:buf_nr_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81015962)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff812276ac)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff81290258)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffff812a6935)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/buffer.c (ffffffff813198f5)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff81322def)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8139e988)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813ad3cb)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813bb282)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c42a7)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c4bdf)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff813d1ebd)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff813ea39c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81628768)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff81848929)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100dbe5)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:buf_nr_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81014c32)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff8121a81c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff81281ee8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffff812983d5)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/buffer.c (ffffffff8130a4b5)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8131398f)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8138f418)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff8139de5b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813abd12)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813b4d27)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813b565f)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff813c293d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff813dae1c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/md/md-bitmap.c (ffffffff8180ff89)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100ee45)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:buf_nr_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81015922)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff8122544c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128e068)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffff812a4745)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/buffer.c (ffffffff813173c5)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813208bf)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff8139c1e8)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813aac2b)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813b8ae2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813c1737)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813c206f)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff813cf34d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff813e771c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81656738)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff81897f59)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In arch/x86/events/intel/bts.c (ffffffff8100f015)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:buf_nr_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81015b62)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In mm/page-writeback.c (ffffffff8123474c)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129de0a)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/migrate.c (ffffffff812b52a5)
Location: include/linux/page-flags.h:349
Inline: True
```
```
In fs/buffer.c (ffffffff81328fb5)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:__getblk_gfp
  - fs/buffer.c:init_page_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff813325df)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/inline.c (ffffffff813b0708)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffff813bf576)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_set_page_dirty
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/move_extent.c (ffffffff813cd802)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/page-io.c (ffffffff813d6897)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813d71ef)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff813e468d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
```
In fs/jbd2/transaction.c (ffffffff813fceca)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
```
```
In drivers/xen/grant-table.c (ffffffff81670d18)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_pages_clear_private
```
```
In drivers/md/md-bitmap.c (ffffffff818b4149)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
</ul>

## Differences
