# Function: <code>constant_test_bit_acquire</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fb7ce)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sched/build_utility.c (0)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
```
```
In mm/ksm.c (ffffffff8141dc03)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff814a4448)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In fs/buffer.c (ffffffff814d33d9)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff814da4f9)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff81557291)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155b44f)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff8156d63f)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff8158061a)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81587326)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81592308)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff8159833f)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/move_extent.c (ffffffff8159943b)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff8159dd29)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815c2b5d)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff815ccc42)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/transaction.c (ffffffff815ddb4b)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff815e0351)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815e0fa9)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff815e881a)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff815f8f78)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81605107)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
```
In security/keys/gc.c (ffffffff8164ddd3)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff81656c90)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81d10caa)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff8110786e)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sched/build_utility.c (0)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
```
```
In mm/ksm.c (ffffffff81452543)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In mm/migrate.c (ffffffff81469bb0)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/inode.c (ffffffff814d95bf)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In fs/buffer.c (ffffffff8150a669)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff8150ead0)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff8158f111)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8159326d)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff815a552f)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff815b7bda)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815bd9e6)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c93ea)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff815ced83)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/move_extent.c (ffffffff815cfd91)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff815d458d)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff815fa2bd)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff81604732)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/transaction.c (ffffffff816155cf)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff81617bfd)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618899)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff8162041a)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff81630ed8)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff8163d017)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
```
In security/keys/gc.c (ffffffff81686593)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff8168f510)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81d7a13a)
Location: arch/x86/include/asm/bitops.h:210
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff811111cc)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sched/build_utility.c (0)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
```
```
In mm/ksm.c (ffffffff8148cbd3)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In mm/migrate.c (ffffffff81498b3d)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/inode.c (ffffffff8150bd6a)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In fs/buffer.c (ffffffff8153f619)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__bh_read
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_is_partially_uptodate
  - fs/buffer.c:__block_commit_write
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:iomap_to_bh
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__breadahead
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/mpage.c (ffffffff815433cd)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/balloc.c (ffffffff815c7e21)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_wait_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cbf5d)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/ialloc.c (ffffffff815de39f)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff815f0963)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815f67a6)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff816021ca)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_prefetch
```
```
In fs/ext4/mmp.c (ffffffff81607613)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/move_extent.c (ffffffff8160860e)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff8160cc3d)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
```
In fs/ext4/super.c (ffffffff81632ebd)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:update_super_work
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh
  - fs/ext4/super.c:ext4_read_bh_nowait
```
```
In fs/ext4/symlink.c (ffffffff8163d3e4)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/jbd2/transaction.c (ffffffff8164e3bc)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
```
```
In fs/jbd2/commit.c (ffffffff81650aef)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651818)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
```
```
In fs/jbd2/journal.c (ffffffff816593ea)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
```
```
In fs/fat/dir.c (ffffffff8166a388)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/misc.c (ffffffff81676587)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_sync_bhs
```
```
In security/keys/gc.c (ffffffff816c2a03)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff816cbaa0)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81e312da)
Location: arch/x86/include/asm/bitops.h:209
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
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
