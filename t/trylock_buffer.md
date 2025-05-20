# Function: <code>trylock_buffer</code>

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
In mm/migrate.c (ffffffff811f0eee)
Location: include/linux/buffer_head.h:347
Inline: True
```
```
In fs/buffer.c (ffffffff8124432a)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
```
```
In fs/ext4/balloc.c (ffffffff8128fcd3)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81293520)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81296403)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/super.c (ffffffff812b8ca5)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/resize.c (ffffffff812bef77)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff812c528e)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff812d7954)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff812d923d)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff812dd0e9)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812dfe6f)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff812e84ec)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812e9bde)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812ec25b)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff812f1939)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In mm/migrate.c (ffffffff81210189)
Location: include/linux/buffer_head.h:351
Inline: True
```
```
In fs/buffer.c (ffffffff8126dbab)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff812bd203)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c0ae1)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c39f6)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/super.c (ffffffff812e7afd)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff812ee882)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff812f4b01)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff813076b6)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff81308ff6)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130d4dc)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/inline.c (ffffffff8130fb20)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff81316e2e)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317e08)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81319d6d)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8131f15c)
Location: include/linux/buffer_head.h:351
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In mm/migrate.c (ffffffff812222b9)
Location: include/linux/buffer_head.h:354
Inline: True
```
```
In fs/buffer.c (ffffffff81280dfb)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff812d2853)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d6111)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812d90a6)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/super.c (ffffffff812fd83d)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff81304852)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff8130aab1)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff8131d6a6)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff8131f006)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff813233d1)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/inline.c (ffffffff81325940)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff8132ce1e)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132ddf0)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8132fd5d)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813351de)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In mm/migrate.c (ffffffff8122db59)
Location: include/linux/buffer_head.h:355
Inline: True
```
```
In fs/buffer.c (ffffffff8128e6db)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff812e3ecf)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e9145)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff812f4491)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff812f7c7f)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff812f9988)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff812ff775)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81314374)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8131f3e6)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff81332593)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8133c829)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81341feb)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342f50)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81344d0b)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81349f7e)
Location: include/linux/buffer_head.h:355
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In mm/migrate.c (ffffffff812496d9)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff812b12cb)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813088bf)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130dbe5)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81318bd1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8131c2bf)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8131dfc8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81323f25)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81338b34)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81343a86)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff81356aa3)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81360dac)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff8136661b)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8136757b)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff813693ab)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8136e5ce)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In mm/migrate.c (ffffffff8126ed29)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff812d912c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8133688c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8133cb5f)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81346c18)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8134a294)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8134bfad)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813508ea)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81367074)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813718b2)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff81384dd1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8138f70e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81394ccb)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395e14)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81397b59)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8139cc2e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In mm/migrate.c (ffffffff81282999)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff812ee5fc)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8134db0c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8135420f)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8135edc8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81362457)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813640ed)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81369d7a)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8137f4f4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81389d79)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff8139d8c1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813a8095)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813ada3b)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813aeb6a)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b08df)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813b599e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In mm/migrate.c (ffffffff8129eb2e)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff8130fdf3)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813764f0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137ca04)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8138801d)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138a799)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138dc46)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813931d0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813a8974)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813b47e1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813c7ae1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d2581)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813d7d7f)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d904c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dae6e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e026e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
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
In mm/migrate.c (ffffffff812ae3ce)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff81322dc3)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8138e760)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81395104)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813a09e2)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813a31e9)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813a66a6)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813abb5e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813c1884)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813cd6e1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813e0ea1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813ebc61)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813f1e4f)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f3045)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4ebe)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813fa2ae)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81405639)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81408939)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff812e4db0)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff8135d833)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813d9f1b)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813ddd6c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813eccb1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ef3cc)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813f257a)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813f7e98)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8140dbe1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81419b3d)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff8142da73)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81438e49)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff8143f460)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81440921)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81442214)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8144787e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81453609)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814562bd)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff812ef790)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff8136b423)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813ebbc5)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813ef65c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff813fb0e3)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff813feebc)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81401b1c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81404cca)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81409b92)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141513f)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff8142104c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142a21c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/resize.c (ffffffff8142d546)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff81446733)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81451972)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_update_super_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff8145428b)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/transaction.c (ffffffff8145b6c0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8145cb4e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8145e565)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814641fe)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8146fab9)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147267d)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff812f6480)
Location: include/linux/buffer_head.h:359
Inline: True
```
```
In fs/buffer.c (ffffffff81371cc3)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813f2105)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f5b1b)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814015b3)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814051d0)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81408061)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8140b235)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8140fd4a)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141b03c)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff814277fc)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81430f1c)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/resize.c (ffffffff81434206)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8144bee3)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81458970)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff81459bbb)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/transaction.c (ffffffff81461000)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814621e5)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81463dea)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814698ae)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81474f7a)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147808d)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff81340ac0)
Location: include/linux/buffer_head.h:359
Inline: True
```
```
In fs/buffer.c (ffffffff813c0ce3)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff814440e5)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8144837b)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81453b3c)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814579e4)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8145a99d)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8145deb4)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81462e24)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8146df40)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff8147b44d)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81487c69)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8149ff57)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff814aca83)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff814adcab)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff814b184c)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/transaction.c (ffffffff814b64e0)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b76db)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b93bc)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814bfd4e)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff814cd528)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814cf30d)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff813b28f4)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8144503b)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff814bffdb)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff814c48cc)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814d101f)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814d53dc)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d871e)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff814dbc5b)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814e2939)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff814eec97)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff814fd8ad)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8150b546)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff81526b8b)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81534a3f)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/fast_commit.c (ffffffff81535b9b)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff8153a3a3)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8153cd3b)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8153fdd4)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81540eba)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815430e8)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81549d3d)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8155930f)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8155be24)
Location: include/linux/buffer_head.h:381
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff81434258)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff814d33d1)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
```
```
In fs/ext4/balloc.c (ffffffff81557fe6)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8155ce0c)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81569a63)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff8156e33a)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81571506)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81574bbb)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8157bd79)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81588d5b)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff8159808d)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff815a61e9)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815c446b)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff815d2f6c)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:__ext4_xattr_check_block
```
```
In fs/ext4/fast_commit.c (ffffffff815d404b)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff815d8913)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff815db500)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff815de96a)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff815e000d)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815e1f40)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815ea5dd)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff815fc414)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff815fdd1f)
Location: include/linux/buffer_head.h:388
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff81469b99)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8150a661)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
```
```
In fs/ext4/balloc.c (ffffffff8158fd33)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81594c2c)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815a1853)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff815a61fa)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815a926d)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815aca8b)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815b3179)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815bf5d0)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff815ceb3d)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/resize.c (ffffffff815dca59)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815fbb4c)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff8160aaba)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/fast_commit.c (ffffffff8160bc2b)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff816104b4)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff81612fb0)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff816163ca)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81617329)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8161975c)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a7c0)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81620de6)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff816343a4)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81635cd0)
Location: include/linux/buffer_head.h:401
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff81498b26)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8153f611)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
```
```
In fs/ext4/balloc.c (ffffffff815c88c2)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815cd8dc)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815da603)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff815df079)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e7c)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815e582a)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815ebf7a)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815f8376)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff816073bd)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/resize.c (ffffffff8161533f)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff816346ec)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
```
```
In fs/ext4/xattr.c (ffffffff8164386a)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/fast_commit.c (ffffffff816449eb)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff81649274)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8164bdb0)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8164f1ec)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81650143)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81652681)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/checkpoint.c (ffffffff816536e7)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81659a26)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8166d883)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f1bf)
Location: include/linux/buffer_head.h:392
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffff800010350228)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffff8000103dbea4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffff8000104609b8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010467e4c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffff800010474078)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffff800010476ab0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffff800010479f94)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff8000104803b0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffff80001049904c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffff8000104a6c64)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffff8000104ba218)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffff8000104c4b00)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffff8000104cc314)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce6c0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d081c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffff8000104d713c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffff8000104e49f4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffff8000104e8ea4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (c0551930)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (c05b5220)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (c062115c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0628b6c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c063548c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c06385e4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (c063b7e0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0641798)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c065a9a4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (c0668a68)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (c067d89c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c0688b14)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (c068ff8c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c0691428)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0693484)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c06992c4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (c06a3764)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c06a6db8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (c0000000004340ac)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (c0000000004e3c7c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (c00000000057d010)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c000000000587c44)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c0000000005953d8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c000000000599d48)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c00000000059c1d0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005a49e8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c0000000005c3190)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (c0000000005d3314)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (c0000000005ef91c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c0000000005fc440)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (c000000000605cb8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c00000000060713c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0000000006099e8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c000000000611d6c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (c0000000006224ac)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c0000000006264dc)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffe00023eed4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffe000294404)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffe0002efe86)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f5bc2)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffe0002ffaba)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffe000302b88)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffe000304284)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe00030910e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffe00031cbd8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffe000326c6c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffe000336746)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffe00033f3f8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffe000344ed4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe00034604a)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347f10)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffe00034d09c)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffe0003577fe)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffe000359e06)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff812a69ae)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff8131b3a3)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff81386d40)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138d6e4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81398fc2)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8139b7c9)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139ec86)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a413e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b9e64)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813c5cc1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813d9481)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e4241)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813ea42f)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb625)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ed49e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f288e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813fdc19)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81400f19)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff8129844e)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff8130bf43)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813777d0)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137e174)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81389a52)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138c259)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138f716)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81394bce)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813aa8f4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813b6741)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813c9f01)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d4cc1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813daeaf)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dc0a5)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ddf1e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e330e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813ee699)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813f1999)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff812a47be)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff81318e73)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff81384810)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138b044)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81396822)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81399029)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139c4e6)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a199e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b76c4)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813c3151)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813d6911)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e15c1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813e77af)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e89a5)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea81e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813efc0e)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813faf99)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813fe299)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In mm/migrate.c (ffffffff812b5316)
Location: include/linux/buffer_head.h:357
Inline: True
```
```
In fs/buffer.c (ffffffff8132aaa3)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/buffer.c:ll_rw_block
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8139838b)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139ed7f)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813aaaa8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ae202)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b09fd)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b65b1)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813cc3cf)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813d82fc)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813ebbba)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813f69d2)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813fcf63)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fe1fd)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81400180)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81405627)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81410bc8)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81413f40)
Location: include/linux/buffer_head.h:357
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
</details>
</li>
</ul>

## Differences
