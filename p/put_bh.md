# Function: <code>put_bh</code>

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
In mm/migrate.c (ffffffff811f0f2d)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff81242692)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_read_sync
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:write_boundary_block
```
```
In fs/ext4/balloc.c (ffffffff8128fda7)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81292e52)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff81295cd9)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/ext4/inode.c:bput_one
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/extents.c (ffffffff812c2cb5)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
```
```
In fs/ext4/migrate.c (ffffffff812cc247)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/mballoc.c (ffffffff812d0cb2)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/ext4/mmp.c (ffffffff812d7f58)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/indirect.c (ffffffff812d8558)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/jbd2/commit.c (ffffffff812ead81)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff812eba7e)
Location: include/linux/buffer_head.h:276
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff812ed764)
Location: include/linux/buffer_head.h:276
Inline: True
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
In mm/migrate.c (ffffffff81211174)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff8126dc46)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff812bd816)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c0e24)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/inode.c (ffffffff812c9190)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/extents.c (ffffffff812f2a63)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/migrate.c (ffffffff812fc2d9)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mballoc.c (ffffffff813048ba)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/mmp.c (ffffffff81307cd1)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/indirect.c (ffffffff813082c8)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/jbd2/commit.c (ffffffff81318734)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81319641)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8131b0ca)
Location: include/linux/buffer_head.h:280
Inline: True
```
```
In fs/squashfs/block.c (ffffffff81321028)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81325edf)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813261e1)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813264a9)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8132679b)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
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
In mm/migrate.c (ffffffff81223334)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff81280e96)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff812d2e66)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d6454)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/inode.c (ffffffff812dedd0)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/extents.c (ffffffff81308a33)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/migrate.c (ffffffff81312289)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mballoc.c (ffffffff8131a87a)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/mmp.c (ffffffff8131dcc1)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/indirect.c (ffffffff8131e2b8)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/jbd2/commit.c (ffffffff8132e72a)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8132f631)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813310aa)
Location: include/linux/buffer_head.h:283
Inline: True
```
```
In fs/squashfs/block.c (ffffffff81336ed8)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8133bc8f)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8133bf91)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8133c259)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8133c54b)
Location: include/linux/buffer_head.h:283
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
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
In mm/migrate.c (ffffffff8122db60)
Location: include/linux/buffer_head.h:284
Inline: True
```
```
In fs/buffer.c (ffffffff8128e786)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff812e4476)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e718e)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff812f4716)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff812f6e9c)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81302dfb)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81311c4c)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81313d47)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813148db)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/jbd2/commit.c (ffffffff81343858)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81344859)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8134600a)
Location: include/linux/buffer_head.h:284
Inline: True
```
```
In fs/squashfs/block.c (ffffffff8134bbc5)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8135078e)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81350a7d)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81350deb)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813510c5)
Location: include/linux/buffer_head.h:284
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
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
In mm/migrate.c (ffffffff812496e0)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/buffer.c (ffffffff812b1376)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff81308ea6)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130bb8e)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81318e9c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8131b4dc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813277eb)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81336460)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81338507)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8133909b)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/jbd2/commit.c (ffffffff81367ea6)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81368ef9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff8136a69f)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/squashfs/block.c (ffffffff81370221)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81374f2d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81375234)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813755b5)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8137589f)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81375b7c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In mm/migrate.c (ffffffff8126ede1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page
```
```
In fs/buffer.c (ffffffff812d91d6)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff81336dd0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81339d0d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81346dff)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8134940c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8135548a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81364bbb)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81366a9e)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8136760f)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/jbd2/commit.c (ffffffff813967d2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81397566)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff81398bff)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/squashfs/block.c (ffffffff8139ea04)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813a391a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813a3c21)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813a3fbc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813a42bd)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813a458a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffff812ee6a6)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff8134e050)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81350ead)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8135efaf)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813615cc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8136d7b9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8137cebe)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8137eeee)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8137fa8f)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8139c28c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813af532)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b04cc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813b196f)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/squashfs/block.c (ffffffff813b7782)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813bc71a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813bca21)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813bcdbc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813bd0bd)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813bd38a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffff8130fe96)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff81376a07)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81379ba1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813881f1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8138a65d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81396de5)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813a6b2e)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813a8334)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813a8eea)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813c64f1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813d9a7e)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813da954)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/revoke.c (ffffffff813dbfa3)
Location: include/linux/buffer_head.h:286
Inline: True
```
```
In fs/squashfs/block.c (ffffffff813e1f27)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813e6fc2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813e72c9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813e7664)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813e7972)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813e7c45)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffff81322e66)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff8138ec77)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813920c1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813a0bb6)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813a30ad)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813af815)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813bf9b1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813c11e1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813c1e0a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813df8b1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813f3ce7)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f49a4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813fbf57)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81401042)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81401349)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814016e4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814019f2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81401cc5)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffff81359e39)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff813da229)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813de82f)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813ecc9e)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813ef27d)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813fb82d)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8140ba45)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8140d79a)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8140e06b)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8142c205)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff81441114)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81441ea5)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
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
In fs/buffer.c (ffffffff81367f69)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff813ebefb)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f00d8)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813feea9)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff814019d1)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff8140dfa6)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8141eee0)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81420c00)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff814214fb)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff81444f7d)
Location: include/linux/buffer_head.h:280
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff8145d315)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff8145e05c)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:calc_chksums
```
```
In fs/jbd2/journal.c (ffffffff8146055a)
Location: include/linux/buffer_head.h:280
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
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
In fs/buffer.c (ffffffff8136e959)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff813f2429)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f6365)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81405388)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff81407f13)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81414166)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff814258ee)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff814273bb)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff81427cb5)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8144a89e)
Location: include/linux/buffer_head.h:282
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81462c3e)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814637cc)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81465d0a)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
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
In fs/buffer.c (ffffffff813bd7e5)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff814443f9)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81448bf0)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81457bae)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8145a823)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff814674c6)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8147953f)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff8147b04b)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff8147b995)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff8149e35f)
Location: include/linux/buffer_head.h:282
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff814b8134)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b8d5d)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814bb7fa)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
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
In fs/buffer.c (ffffffff814439c5)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff814c02c8)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff814c5a30)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff814d559b)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff814d8573)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff814e70c8)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff814f5b3a)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff814fd49f)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff814fde83)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff81524965)
Location: include/linux/buffer_head.h:304
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff815419d4)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815429b4)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8154589a)
Location: include/linux/buffer_head.h:304
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
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
In fs/buffer.c (ffffffff814d2f15)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff81558308)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8155dfb0)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8156e379)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8157133e)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81580a8b)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff8158fdda)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81597c6b)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff81598674)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815c1dda)
Location: include/linux/buffer_head.h:317
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff815e0620)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff815e16c0)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815e4b7a)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
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
In fs/buffer.c (ffffffff81509922)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff81590078)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81595dcc)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815a6239)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff815a90b1)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815b803b)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff815c724c)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff815ce6d4)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff815cf143)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff815f955a)
Location: include/linux/buffer_head.h:330
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81617ecb)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81618ece)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8161c4da)
Location: include/linux/buffer_head.h:330
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
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
In fs/buffer.c (ffffffff8153e752)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lrus_cpu
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:__bforget
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff815c8c08)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815cea7c)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815df0b8)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff815e2310)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff815f0ddb)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff81604bc2)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff81606f54)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff816079db)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff816320ea)
Location: include/linux/buffer_head.h:300
Inline: True
```
```
In fs/jbd2/commit.c (ffffffff81650dd6)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81651d89)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff816553ea)
Location: include/linux/buffer_head.h:300
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_fc_release_bufs
  - fs/jbd2/journal.c:jbd2_fc_wait_bufs
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
In fs/buffer.c (ffff8000103dc018)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffff8000104611b0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff80001046592c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff8000104743d4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffff800010477628)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffff800010485760)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffff8000104964f0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffff8000104989c0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffff800010499584)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffff8000104b8608)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffff8000104cf2b0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffff8000104d0184)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffff8000104d9bbc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffff8000104df314)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffff8000104df5ac)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffff8000104df954)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffff8000104dfc80)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffff8000104dffb0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (c05b5334)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (c0621868)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0624fd0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c063584c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c0638310)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (c0645830)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (c0658684)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (c065a294)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (c065b010)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (c067beb4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (c0691f84)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c0692ed8)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (c069b474)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (c06a0c84)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (c06a0f08)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (c06a1204)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (c06a1570)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (c06a186c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (c0000000004de164)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (c00000000057d8cc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0000000005820a4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c00000000059562c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (c000000000598a58)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (c0000000005a93d0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (c0000000005c0498)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (c0000000005c29a0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (c0000000005c39e4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (c0000000005ed7c4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (c000000000607cd8)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c000000000609544)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (c0000000006145ac)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (c00000000061b41c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (c00000000061b7ec)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (c00000000061bc64)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (c00000000061c13c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (c00000000061c558)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffe000291a36)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:buffer_exit_cpu_dead
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/buffer.c:__bforget
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffe0002f0488)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f2dc4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffe0002ffd66)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffe000302138)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffe00030c746)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffe00031b13a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffe00031c60e)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffe00031d0d0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffe00033510c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffe000346d7a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe0003478cc)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffe00034ed04)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffe0003538b0)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffe000353b0a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffe000353d72)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffe000353ff4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffe0003542a4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffff8131b446)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff81387257)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138a6a1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81399196)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8139b68d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813a7df5)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813b7f91)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813b97c1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813ba3ea)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813d7e91)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813ec2c7)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ecf84)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813f4537)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813f9622)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813f9929)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f9cc4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813f9fd2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813fa2a5)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffff8130bfe6)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff81377ce7)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137b131)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81389c26)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff8138c11d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff81398885)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813a8a21)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813aa251)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813aae7a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813c8911)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813dcd47)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dda04)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813e4fb7)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813ea0a2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813ea3a9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813ea744)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813eaa52)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813ead25)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffff81318f16)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff81384d27)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81388001)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813969f6)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff81398eed)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813a5655)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813b57f1)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813b7021)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813b7c4a)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813d5321)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813e9647)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea304)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff813f18b7)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff813f69a2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff813f6ca9)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff813f7044)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff813f7352)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff813f7625)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
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
In fs/buffer.c (ffffffff8132ab46)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/buffer.c:write_boundary_block
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_read_sync
```
```
In fs/ext4/balloc.c (ffffffff813988a7)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139bd01)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813aacab)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_end_bitmap_read
```
```
In fs/ext4/indirect.c (ffffffff813ad30d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inode.c (ffffffff813b9d95)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_bread
```
```
In fs/ext4/mballoc.c (ffffffff813ca475)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
```
```
In fs/ext4/migrate.c (ffffffff813cbd31)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/mmp.c (ffffffff813cc94d)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
```
```
In fs/ext4/super.c (ffffffff813ea5a4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/jbd2/commit.c (ffffffff813fef42)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ffc5c)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/squashfs/block.c (ffffffff814074bb)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8140c632)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8140c939)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8140ccd4)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8140cfe2)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8140d2b5)
Location: include/linux/buffer_head.h:286
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
</ul>

## Differences
