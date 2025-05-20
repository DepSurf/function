# Function: <code>__getblk_gfp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243ea0)
Location: fs/buffer.c:1390
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81243ea0-ffffffff81243f00: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126ccb0)
Location: fs/buffer.c:1380
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8126ccb0-ffffffff8126cd10: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127fc60)
Location: fs/buffer.c:1380
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8127fc60-ffffffff8127ff95: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128d210)
Location: fs/buffer.c:1375
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8128d210-ffffffff8128d4df: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812afd50)
Location: fs/buffer.c:1335
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff812afd50-ffffffff812b0037: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1306
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff812daf02-ffffffff812daf4c: __getblk_gfp.cold.62 (STB_LOCAL)
ffffffff812d7fa0-ffffffff812d8227: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1314
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff812f03cb-ffffffff812f0415: __getblk_gfp.cold.65 (STB_LOCAL)
ffffffff812ed010-ffffffff812ed297: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81311cad-ffffffff81311cf8: __getblk_gfp.cold (STB_LOCAL)
ffffffff8130e7c0-ffffffff8130ea50: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81324cba-ffffffff81324d09: __getblk_gfp.cold (STB_LOCAL)
ffffffff813217e0-ffffffff81321a6c: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135cb55)
Location: fs/buffer.c:1348
Inline: True
Inline callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8135bee0-ffffffff8135bf3e: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136aecd)
Location: fs/buffer.c:1347
Inline: True
Inline callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8136a480-ffffffff8136a4de: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1352
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81bdcb3a-ffffffff81bdcb86: __getblk_gfp.cold (STB_LOCAL)
ffffffff81370fe0-ffffffff813710b8: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1327
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81cc47b8-ffffffff81cc4843: __getblk_gfp.cold (STB_LOCAL)
ffffffff813c09b0-ffffffff813c0a95: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1326
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff81e76fb1-ffffffff81e77038: __getblk_gfp.cold (STB_LOCAL)
ffffffff81445980-ffffffff81445a74: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1326
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff820690d5-ffffffff82069114: __getblk_gfp.cold (STB_LOCAL)
ffffffff814d4a00-ffffffff814d4b31: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150c8dd)
Location: fs/buffer.c:1438
Inline: True
Inline callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_breadahead_unmovable
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/jbd2/journal.c:jbd2_fc_get_buf
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8150c750-ffffffff8150c7c8: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103da158)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffff8000103da158-ffff8000103da480: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b3a08)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
c05b3a08-c05b3a80: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004df120)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
c0000000004df120-c0000000004df554: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000292f62)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffe000292f62-ffffffe0002931f8: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8131d29a-ffffffff8131d2e9: __getblk_gfp.cold (STB_LOCAL)
ffffffff81319dc0-ffffffff8131a04c: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8130de3a-ffffffff8130de89: __getblk_gfp.cold (STB_LOCAL)
ffffffff8130a960-ffffffff8130abec: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8131ad6a-ffffffff8131adb9: __getblk_gfp.cold (STB_LOCAL)
ffffffff81317890-ffffffff81317b1c: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__getblk_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1315
Inline: False
Direct callers:
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__breadahead
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
  - fs/ext4/super.c:ext4_sb_bread
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/recovery.c:jread
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/fatent.c:fat_mirror_bhs
```
**Symbols:**

```
ffffffff8132ca0b-ffffffff8132ca5a: __getblk_gfp.cold (STB_LOCAL)
ffffffff81329490-ffffffff81329717: __getblk_gfp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
