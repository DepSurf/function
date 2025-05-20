# Function: <code>lock_buffer</code>

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
In mm/migrate.c (ffffffff811f0f0c)
Location: include/linux/buffer_head.h:352
Inline: True
```
```
In fs/buffer.c (ffffffff81244325)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:nobh_write_begin
```
```
In fs/ext4/balloc.c (ffffffff8128fcce)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8129351b)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812963fe)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/super.c (ffffffff812b8ca0)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/resize.c (ffffffff812bef72)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff812c5289)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff812d794f)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff812d9238)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff812dd0e4)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812dfe6a)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff812e84e7)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812e9bd9)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812ec256)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff812f1934)
Location: include/linux/buffer_head.h:352
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void lock_buffer(struct buffer_head *bh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812101b7)
Location: include/linux/buffer_head.h:356
Inline: True
```
```
In fs/buffer.c (ffffffff8126f113)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff812bd1fe)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c0adc)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c39f1)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/super.c (ffffffff812e7af8)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff812ee87d)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff812f4afc)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff813076b1)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff81308ff1)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130d4d7)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/inline.c (ffffffff8130fb1b)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff81316e29)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81317e03)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81319d68)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8131f157)
Location: include/linux/buffer_head.h:356
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff8126bc00-ffffffff8126bc3e: lock_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void lock_buffer(struct buffer_head *bh);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812222e7)
Location: include/linux/buffer_head.h:359
Inline: True
```
```
In fs/buffer.c (ffffffff81282305)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
Direct callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/balloc.c (ffffffff812d284e)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d610c)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812d90a1)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/super.c (ffffffff812fd838)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/resize.c (ffffffff8130484d)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/extents.c (ffffffff8130aaac)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff8131d6a1)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff8131f001)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff813233cc)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/inline.c (ffffffff8132593b)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/transaction.c (ffffffff8132ce19)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8132ddeb)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8132fd58)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813351d9)
Location: include/linux/buffer_head.h:359
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
**Symbols:**

```
ffffffff8127ed40-ffffffff8127ed7e: lock_buffer (STB_LOCAL)
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
In mm/migrate.c (ffffffff8122db8b)
Location: include/linux/buffer_head.h:360
Inline: True
```
```
In fs/buffer.c (ffffffff8128fa20)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff812e3eca)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e9140)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff812f448c)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff812f7c7a)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff812f9983)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff812ff770)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8131436f)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8131f3e1)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff8133258e)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8133c824)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81341fe6)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81342f4b)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81344d06)
Location: include/linux/buffer_head.h:360
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81349f79)
Location: include/linux/buffer_head.h:360
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
In mm/migrate.c (ffffffff8124970b)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff812b270d)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813088ba)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130dbe0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81318bcc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8131c2ba)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8131dfc3)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81323f20)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81338b2f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81343a81)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff81356a9e)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81360da7)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81366616)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81367576)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff813693a6)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8136e5c9)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff8126ed24)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff812da5f4)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff81336887)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8133cb5a)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81346c13)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8134a28f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff8134bfa8)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813508e5)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8136706f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813718ad)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff81384dcc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff8138f709)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff81394cc6)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81395e0f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81397b54)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8139cc29)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff812829e0)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff812efad4)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8134db07)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8135420a)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8135edc3)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81362452)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813640e8)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81369d75)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8137f4ef)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81389d74)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff8139d8bc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813a8090)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813ada36)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813aeb65)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b08da)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813b5999)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff8129eb29)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff81311368)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813764eb)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137c9ff)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81388018)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138a794)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138dc41)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813931cb)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813a896f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813b47dc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813c7adc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d257c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813d7d7a)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813d9047)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dae69)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e0269)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff812ae3c9)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff81324348)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8138e75b)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813950ff)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813a09dd)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813a31e4)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813a66a1)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813abb59)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813c187f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813cd6dc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813e0e9c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813ebc5c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813f1e4a)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813f3040)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4eb9)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813fa2a9)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81405634)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81408934)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff812e4df8)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff8135d82e)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813d9f16)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813ddd67)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813eccac)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ef3c7)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff813f2575)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813f7e93)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8140dbdc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81419b38)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff8142da6e)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff81438e44)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff8143f45b)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8144091c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8144220f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81447879)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81453604)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814562b8)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff812ef7d8)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff8136b41e)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813ebbc0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813ef657)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff813fb0de)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff813feeb7)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81401b17)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81404cc5)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81409b8d)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141513a)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff81421047)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142a217)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/resize.c (ffffffff8142d541)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8144672e)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff8145196d)
Location: include/linux/buffer_head.h:362
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
In fs/ext4/fast_commit.c (ffffffff81454286)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/transaction.c (ffffffff8145b6bb)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8145cb49)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8145e560)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814641f9)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8146fab4)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81472678)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff812f64c8)
Location: include/linux/buffer_head.h:364
Inline: True
```
```
In fs/buffer.c (ffffffff81371cbe)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813f2100)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f5b16)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814015ae)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814051cb)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8140805c)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8140b230)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8140fd45)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8141b037)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff814277f7)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81430f17)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/resize.c (ffffffff81434201)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8144bede)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff8145896b)
Location: include/linux/buffer_head.h:364
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
In fs/ext4/fast_commit.c (ffffffff81459bb6)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/transaction.c (ffffffff81460ffb)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814621e0)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81463de5)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814698a9)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81474f75)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81478088)
Location: include/linux/buffer_head.h:364
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
In mm/migrate.c (ffffffff81340b07)
Location: include/linux/buffer_head.h:364
Inline: True
```
```
In fs/buffer.c (ffffffff813c0cde)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff814440e0)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81448376)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81453b37)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814579df)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8145a998)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8145deaf)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81462e1f)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff8146df3b)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff8147b448)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81487c64)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff8149ff52)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff814aca7e)
Location: include/linux/buffer_head.h:364
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
In fs/ext4/fast_commit.c (ffffffff814adca6)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff814b1847)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/jbd2/transaction.c (ffffffff814b64db)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff814b76d6)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b93b7)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814bfd49)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff814cd523)
Location: include/linux/buffer_head.h:364
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814cf308)
Location: include/linux/buffer_head.h:364
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
In mm/migrate.c (ffffffff813b294a)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffff81445036)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff814bffd6)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff814c48c7)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff814d101a)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff814d53d7)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d8719)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff814dbc56)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814e2934)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff814eec92)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff814fd8a8)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8150b541)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff81526b86)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81534a3a)
Location: include/linux/buffer_head.h:386
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
In fs/ext4/fast_commit.c (ffffffff81535b96)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff8153a39e)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8153cd36)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8153fdcf)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81540eb5)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815430e3)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81549d38)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8155930a)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8155be1f)
Location: include/linux/buffer_head.h:386
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
In mm/migrate.c (ffffffff814342ae)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff814d33cc)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff81557fe1)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8155ce07)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff81569a5e)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff8156e335)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81571501)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff81574bb6)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8157bd74)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff81588d56)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff81598088)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff815a61e4)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815c4466)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff815d2f67)
Location: include/linux/buffer_head.h:393
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
In fs/ext4/fast_commit.c (ffffffff815d4046)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff815d890e)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff815db4fb)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff815de965)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff815e0008)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815e1f3b)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815ea5d8)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff815fc40f)
Location: include/linux/buffer_head.h:393
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff815fdd1a)
Location: include/linux/buffer_head.h:393
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
In mm/migrate.c (ffffffff81469bba)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8150a65c)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8158fd2e)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81594c27)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815a184e)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff815a61f5)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815a9268)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815aca86)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815b3174)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815bf5cb)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff815ceb38)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/resize.c (ffffffff815dca54)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff815fbb47)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff8160aab5)
Location: include/linux/buffer_head.h:406
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
In fs/ext4/fast_commit.c (ffffffff8160bc26)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff816104af)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff81612fab)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff816163c5)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff81617324)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81619757)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81620de1)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8163439f)
Location: include/linux/buffer_head.h:406
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81635ccb)
Location: include/linux/buffer_head.h:406
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
In mm/migrate.c (ffffffff81498b47)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
```
```
In fs/buffer.c (ffffffff8153f60c)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:__bh_read_batch
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:bh_uptodate_or_lock
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:block_invalidate_folio
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff815c88bd)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815cd8d7)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/file.c (ffffffff815da5fe)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/ialloc.c (ffffffff815df074)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e77)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff815e5825)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815ebf75)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/ioctl.c (ffffffff815f8371)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mmp.c (ffffffff816073b8)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/resize.c (ffffffff8161533a)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_update_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
```
```
In fs/ext4/super.c (ffffffff816346e7)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_update_super
```
```
In fs/ext4/xattr.c (ffffffff81643865)
Location: include/linux/buffer_head.h:397
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
In fs/ext4/fast_commit.c (ffffffff816449e6)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/ext4/orphan.c (ffffffff8164926f)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/ext4/crypto.c (ffffffff8164bdab)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
```
```
In fs/jbd2/transaction.c (ffffffff8164f1e7)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidate_folio
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff8165013e)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8165267c)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81659a21)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff8166d87e)
Location: include/linux/buffer_head.h:397
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f1ba)
Location: include/linux/buffer_head.h:397
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
In mm/migrate.c (ffff80001035034c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffff8000103dd6a4)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffff8000104609b4)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff800010467e48)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffff800010474074)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffff800010476aac)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffff800010479f8c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff8000104803ac)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffff800010499048)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffff8000104a6c60)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffff8000104ba214)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffff8000104c4afc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffff8000104cc310)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffff8000104ce6bc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d0814)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffff8000104d7138)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffff8000104e49f0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffff8000104e8ea0)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (c05519ec)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (c05b6bc8)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (c0621158)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0628b68)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c0635488)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c06385e0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (c063b7dc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0641794)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c065a9a0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (c0668a64)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (c067d898)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c0688b10)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (c068ff88)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c0691424)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0693480)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c06992bc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (c06a3760)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c06a6db4)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (c000000000433f30)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (c0000000004e3c70)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (c00000000057d008)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c000000000587c3c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c0000000005953d0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c000000000599d40)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (c00000000059c1c8)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005a49e0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c0000000005c3188)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (c0000000005d330c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (c0000000005ef914)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (c0000000005fc438)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (c000000000605cb0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (c000000000607134)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0000000006099e0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c000000000611d60)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (c0000000006224a4)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c0000000006264cc)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffe00023eedc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/buffer.c (ffffffe0002956e2)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffe0002efe7e)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f5bba)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffe0002ffab2)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffe000302b80)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffe00030427c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe000309106)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffe00031cbd0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffe000326c64)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffe00033673e)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffe00033f3f0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffe000344ecc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffe000346042)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347f08)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffe00034d094)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_mark_journal_empty
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffe0003577fe)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffe000359e06)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff812a69a9)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff8131c928)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff81386d3b)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138d6df)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81398fbd)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8139b7c4)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139ec81)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a4139)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b9e5f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813c5cbc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813d947c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e423c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813ea42a)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813eb620)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ed499)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f2889)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813fdc14)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81400f14)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff81298449)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff8130d4c8)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff813777cb)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137e16f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81389a4d)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138c254)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8138f711)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81394bc9)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813aa8ef)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813b673c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813c9efc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813d4cbc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813daeaa)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813dc0a0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ddf19)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e3309)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813ee694)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813f1994)
Location: include/linux/buffer_head.h:362
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
In mm/migrate.c (ffffffff812a47b9)
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff8131a3f8)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8138480b)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138b03f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8139681d)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81399024)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
```
```
In fs/ext4/inline.c (ffffffff8139c4e1)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a1999)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b76bf)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813c314c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813d690c)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813e15bc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/jbd2/transaction.c (ffffffff813e77aa)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813e89a0)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea819)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813efc09)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff813faf94)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813fe294)
Location: include/linux/buffer_head.h:362
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
Location: include/linux/buffer_head.h:362
Inline: True
```
```
In fs/buffer.c (ffffffff8132c0e9)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:block_invalidatepage
  - fs/buffer.c:__bread_gfp
```
```
In fs/ext4/balloc.c (ffffffff8139838b)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139ed7f)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813aaaa8)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ae202)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b09fd)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b65b1)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813cc3cf)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813d82fc)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff813ebbba)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/ext4/xattr.c (ffffffff813f69d2)
Location: include/linux/buffer_head.h:362
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
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:do_get_write_access
```
```
In fs/jbd2/commit.c (ffffffff813fe1fd)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81400180)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81405627)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_update_sb_errno
  - fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
```
```
In fs/fat/dir.c (ffffffff81410bc8)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81413f40)
Location: include/linux/buffer_head.h:362
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
