# Function: <code>sb_getblk</code>

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
In fs/ext4/balloc.c (ffffffff8128fc9d)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812934ea)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812963a5)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/resize.c (ffffffff812bec06)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/resize.c:bclean
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812c5b74)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff812d7a7f)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff812d84f1)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/xattr.c (ffffffff812dd9c6)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812dfe41)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/fat/dir.c (ffffffff812f614f)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff812f9429)
Location: include/linux/buffer_head.h:313
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/ext4/balloc.c (ffffffff812bd1cd)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812c20af)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812c3b76)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/resize.c (ffffffff812ef2df)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/extents.c (ffffffff812f53bf)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff813077e8)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff81308fc0)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/xattr.c (ffffffff8130d354)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff8130faf2)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/squashfs/block.c (ffffffff81320dab)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81329a45)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8132d04c)
Location: include/linux/buffer_head.h:317
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/ext4/balloc.c (ffffffff812d281d)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff812d76fa)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inode.c (ffffffff812d9226)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/resize.c (ffffffff813052af)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/extents.c (ffffffff8130b36f)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/mmp.c (ffffffff8131d7d8)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/indirect.c (ffffffff8131efd0)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/xattr.c (ffffffff81323249)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff81325912)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/squashfs/block.c (ffffffff81336c5b)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff8133f785)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81342d8c)
Location: include/linux/buffer_head.h:320
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/ext4/balloc.c (ffffffff812e3e9d)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff812e99a2)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff812f5a5a)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff812f7c49)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff812f995a)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff812ff83c)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81314430)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813209ac)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff8133cb05)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff8134b8b3)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813543b0)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81357865)
Location: include/linux/buffer_head.h:321
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/ext4/balloc.c (ffffffff8130888d)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8130e442)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
```
In fs/ext4/ialloc.c (ffffffff81318b9a)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8131c289)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff8131df9a)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81323fec)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81338bf0)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813450c1)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff813610b6)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff8136feeb)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81378fd0)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8137c5c5)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/ext4/balloc.c (ffffffff81336832)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8133a5e5)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81346abf)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8134a26f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff8134bf7f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81350a0e)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813671c1)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81373010)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff8138f317)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff8139e78f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813a7a37)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813aaf33)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/ext4/balloc.c (ffffffff8134dab2)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81351968)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8135ec6f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81362432)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff813640bf)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81369e9e)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8137f641)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8138b463)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff8139c22f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff813a7d64)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff813b750d)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813c0827)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813c3cb3)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/ext4/balloc.c (ffffffff81376492)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137b226)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81387ecf)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138a76b)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff8138dc18)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813932f2)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813a8aac)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813b45b5)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813c6491)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff813d2122)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff813e1c97)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813eb01f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813ee8bb)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
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
In fs/ext4/balloc.c (ffffffff8138e702)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813936f6)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813a087f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813a31bb)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff813a6678)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813abbbe)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813c19bc)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813cd4b5)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813df851)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff813eb802)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff813fbcc7)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff814055fb)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81408907)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (ffffffff813d9ec2)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813dfa21)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813ecc47)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ef39e)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff813f254c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813f7efa)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8140dcdb)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81419af8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff8142c191)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff81439227)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (ffffffff814535cb)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8145628b)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (ffffffff813ebb75)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f12e1)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813fee52)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81401aee)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff81404c9c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81409be5)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff81421108)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8142d798)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff81451d50)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (ffffffff8146fa7b)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147264b)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (ffffffff813f20b5)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff813f7765)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8140505f)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81408034)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff8140b208)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8140fda0)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff814278b8)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81434454)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff81457483)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (ffffffff81474f3d)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8147805b)
Location: include/linux/buffer_head.h:325
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
In fs/ext4/balloc.c (ffffffff81444095)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81449240)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8145785f)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8145a970)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff8145de87)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81462e73)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff8147b545)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81487ec5)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff814ab58f)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (ffffffff814cd4d4)
Location: include/linux/buffer_head.h:325
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff814cf2db)
Location: include/linux/buffer_head.h:325
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
In fs/ext4/balloc.c (ffffffff814bff90)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff814c51c8)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff814d538a)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d86f9)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff814dbc2e)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff814e2a61)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff814fd9cf)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff8150d4a1)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff81532ff6)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (ffffffff815592bb)
Location: include/linux/buffer_head.h:347
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8155bdf2)
Location: include/linux/buffer_head.h:347
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
In fs/ext4/balloc.c (ffffffff81557fa0)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8155d727)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff8156e30d)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815714e1)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff81574b8e)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8157bead)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff815981af)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff815a8223)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff815d174a)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (ffffffff815fc3c0)
Location: include/linux/buffer_head.h:354
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff815fdcf1)
Location: include/linux/buffer_head.h:354
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
In fs/ext4/balloc.c (ffffffff8158fced)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81595541)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff815a61cd)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815a9248)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff815aca5e)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815b32ad)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff815cec5f)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff815deaa3)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff81609288)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (ffffffff81634350)
Location: include/linux/buffer_head.h:367
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81635ca2)
Location: include/linux/buffer_head.h:367
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
In fs/ext4/balloc.c (ffffffff815c886d)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff815ce1d9)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff815df03d)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e1e43)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff815e57ee)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff815ec0a9)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff816074e3)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff81617553)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/xattr.c (ffffffff81641fc8)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/fat/dir.c (ffffffff8166d820)
Location: include/linux/buffer_head.h:358
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff8166f182)
Location: include/linux/buffer_head.h:358
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
In fs/ext4/balloc.c (ffff800010460984)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffff8000104663dc)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffff800010474044)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffff800010476a94)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffff800010479f70)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff8000104803f8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffff800010499180)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffff8000104a5c1c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffff8000104b8594)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffff8000104c47a8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffff8000104d9964)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffff8000104e49c4)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffff8000104e8e7c)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (c062111c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c0626e4c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c063544c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c06385b8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (c063b7b0)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c064180c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c065aad8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (c0667c90)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (c067be34)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (c0688750)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (c069b18c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (c06a3724)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c06a6d84)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (c00000000057cfd0)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (c000000000584220)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (c000000000595390)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c000000000599d20)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (c00000000059c1a4)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005a4a54)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (c0000000005c3330)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (c0000000005d30a0)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (c0000000005ed72c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (c0000000005fc0a4)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (c0000000006142b8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (c000000000622464)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (c0000000006264ac)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (ffffffe0002efe58)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffe0002f44e6)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffe0002ffa8c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffe000302b4c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffe000304264)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe000309150)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffe00031ccd4)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffe000326a82)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffe0003350ae)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffe00033f0d0)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffe00034eb02)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffe000357858)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffe000359e4c)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (ffffffff81386ce2)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8138bcd6)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff81398e5f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8139b79b)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff8139ec58)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a419e)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b9f9c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813c5a95)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813d7e31)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff813e3de2)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff813f42a7)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813fdbdb)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81400ee7)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (ffffffff81377772)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8137c766)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813898ef)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8138c22b)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff8138f6e8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81394c2e)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813aaa2c)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813b6515)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813c88b1)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff813d4862)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff813e4d27)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813ee65b)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813f1967)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (ffffffff813847b2)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff81389636)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813966bf)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff81398ffb)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff8139c4b8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a19fe)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813b77fc)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813c2f25)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813d52c1)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff813e1162)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff813f1627)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813faf5b)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff813fe267)
Location: include/linux/buffer_head.h:323
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
In fs/ext4/balloc.c (ffffffff81398332)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/extents.c (ffffffff8139d349)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_split
```
```
In fs/ext4/ialloc.c (ffffffff813aa91f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ae1db)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_get_branch
```
```
In fs/ext4/inline.c (ffffffff813b09d8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b6616)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_getblk
```
```
In fs/ext4/mmp.c (ffffffff813cc4ff)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
```
```
In fs/ext4/resize.c (ffffffff813d80d5)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_get_bitmap
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:bclean
```
```
In fs/ext4/super.c (ffffffff813ea54f)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sb_bread
```
```
In fs/ext4/xattr.c (ffffffff813f657d)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/squashfs/block.c (ffffffff81407237)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81410b96)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_new_entries
  - fs/fat/dir.c:fat_alloc_new_dir
```
```
In fs/fat/fatent.c (ffffffff81413f17)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_mirror_bhs
```
</details>
</li>
</ul>

## Differences
