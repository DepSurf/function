# Function: <code>ext4_has_feature_metadata_csum</code>

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
In fs/ext4/bitmap.c (ffffffff8129043b)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
```
```
In fs/ext4/ialloc.c (ffffffff81295103)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81299d84)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff812a070f)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a1857)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/super.c (ffffffff812ada41)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812c0913)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812c2a91)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/mmp.c (ffffffff812d7a19)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff812dce74)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
```
In fs/ext4/inline.c (ffffffff812dffac)
Location: fs/ext4/ext4.h:1702
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
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
In fs/ext4/bitmap.c (ffffffff812bdccb)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/ialloc.c (ffffffff812c283e)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812c7c17)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff812cfce9)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812d5cd0)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff812ead86)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/resize.c (ffffffff812f006f)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff812f2453)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/mmp.c (ffffffff81307775)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff8130d5cf)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/inline.c (ffffffff8130fc5c)
Location: fs/ext4/ext4.h:1770
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
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
In fs/ext4/bitmap.c (ffffffff812d331b)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/ialloc.c (ffffffff812d7e54)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812dd777)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff812e5ade)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812eb9d0)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (ffffffff81300c56)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/resize.c (ffffffff8130603f)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/extents.c (ffffffff81308423)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/mmp.c (ffffffff8131d765)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/xattr.c (ffffffff81322915)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/inline.c (ffffffff81325a80)
Location: fs/ext4/ext4.h:1755
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
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
In fs/ext4/bitmap.c (ffffffff812e4806)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff812e6bd5)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff812f6d18)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_has_metadata_csum
```
```
In fs/ext4/inline.c (ffffffff812f9ad6)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81301861)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81308a48)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff81314463)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8131b6e1)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/resize.c (ffffffff81321263)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81335b14)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/xattr.c (ffffffff8133a925)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/bitmap.c (ffffffff81309236)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8130b57f)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff8131b33b)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_has_metadata_csum
```
```
In fs/ext4/inline.c (ffffffff8131e10f)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81326219)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8132d5e2)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mmp.c (ffffffff81338c1c)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8133fd12)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/resize.c (ffffffff81345992)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8135a011)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/xattr.c (ffffffff8135ed05)
Location: fs/ext4/ext4.h:1720
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff81336b22)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff81337166)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8133978a)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81348af2)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8134c104)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813545b4)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8135bd8a)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
```
```
In fs/ext4/mballoc.c (ffffffff8136285c)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffff81367124)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8136dc51)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff81374708)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8138804a)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff8138d685)
Location: fs/ext4/ext4.h:1723
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff8134dda2)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff8134e3e6)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8135092a)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81360ca2)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff81364244)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff8136c8dd)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff81374103)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff8137aa6c)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffff8137f5a4)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813860d1)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff8138cc92)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff813a0c1e)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813a6295)
Location: fs/ext4/ext4.h:1736
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff81376782)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff81376da6)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813795a2)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81389dcb)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8138dd97)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81395eb0)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8139de16)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff813a4be6)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffff813a8a22)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813abad4)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff813b7340)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813cb475)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813d0015)
Location: fs/ext4/ext4.h:1756
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff8138e9f2)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff8138f016)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff813907df)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81391af1)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff813a26d9)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813a67f7)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813ae8a0)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813b65dc)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff813bda56)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffff813c1932)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c9f07)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff813d02c8)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813e482c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813e96e5)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:1909
Inline: True
```
```
In fs/ext4/bitmap.c (ffffffff813da5a6)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff813dbdc4)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813dd5d3)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff813ee3b6)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813f19d5)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff813fa900)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8140206b)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff81409a15)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/mmp.c (ffffffff8140dc80)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8141586f)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_dx_csum_verify
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff8141a3dc)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff81431cbb)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:set_journal_csum_feature_set
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff81436ef1)
Location: fs/ext4/ext4.h:1909
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (0)
Location: fs/ext4/ext4.h:2034
Inline: True
```
```
In fs/ext4/bitmap.c (ffffffff813ec276)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff813ed302)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813eeec3)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81400f03)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff81404075)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8140cf7e)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81414944)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff8141da25)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/mmp.c (ffffffff814210cb)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81429289)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_dx_csum_verify
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff8142e0fe)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff8144aac1)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:set_journal_csum_feature_set
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/xattr.c (ffffffff8144f9f1)
Location: fs/ext4/ext4.h:2034
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff813f2299)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff813f27c1)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff813f3965)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/extents.c (ffffffff813f536c)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81407432)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8140a554)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814130fa)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8141a90e)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff81424196)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/mmp.c (ffffffff8142787b)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8142fd8c)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff81434dbb)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff8145046a)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/xattr.c (ffffffff814551e1)
Location: fs/ext4/ext4.h:2043
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff81444279)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff814447a1)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff81445a28)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81446c45)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
```
In fs/ext4/extents.c (ffffffff81447aa8)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81459cdb)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8145d164)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8146644f)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8146dbc6)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff81477e38)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/mmp.c (ffffffff8147b4e3)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff814843dc)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff8148884d)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff814a70f4)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff814a9641)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/orphan.c (ffffffff814b2185)
Location: fs/ext4/ext4.h:2109
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
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
In fs/ext4/balloc.c (ffffffff814c015c)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff814c0701)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff814c20c9)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c2f26)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
```
In fs/ext4/extents.c (ffffffff814c3fc9)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff814d79a3)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff814db983)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff814e5f6b)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff814ee7f5)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff814fa2ff)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/mmp.c (ffffffff814fd955)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81507228)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff8150b8c0)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff8152ba58)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff81531111)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
```
In fs/ext4/orphan.c (ffffffff8153ad6b)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
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
In fs/ext4/balloc.c (ffffffff8155817a)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff815587a1)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff8155a32c)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155b2a6)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
```
In fs/ext4/extents.c (ffffffff8155c5e5)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81570700)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff815748d3)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff8157f6ea)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff81588738)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff81594b2f)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_prefetch
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/mmp.c (ffffffff81598135)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815a1ceb)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff815a6570)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff815caa88)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_set_def_opts
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff815cf7f8)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_check_block
```
```
In fs/ext4/orphan.c (ffffffff815d932b)
Location: fs/ext4/ext4.h:2121
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
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
In fs/ext4/balloc.c (ffffffff8158fe9c)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff815905ee)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff815920fd)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815930c6)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
```
In fs/ext4/extents.c (ffffffff815943e5)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff815a84de)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff815ac793)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff815b6b9a)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff815bf363)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff815cbb0c)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/mmp.c (ffffffff815cebe5)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff815d8670)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff815dcde0)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff81602b35)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_set_def_opts
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff8160714f)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/orphan.c (ffffffff81610ea7)
Location: fs/ext4/ext4.h:2115
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
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
In fs/ext4/balloc.c (ffffffff815c8a2b)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff815c932e)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff815cae6d)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:__ext4_check_dir_entry
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cbdb6)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_create_access
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
```
In fs/ext4/extents.c (ffffffff815cd0d5)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff815e1293)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff815e5523)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff815ef93a)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff815f8109)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff81601719)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In fs/ext4/mmp.c (ffffffff81607465)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff81610cb4)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dx_node
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff81615812)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_next_flex_gd
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:update_backups
```
```
In fs/ext4/super.c (ffffffff8163b98e)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_set_def_opts
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff8163fe8f)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/ext4/orphan.c (ffffffff81649c67)
Location: fs/ext4/ext4.h:2133
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
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
In fs/ext4/balloc.c (ffff800010460da8)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffff800010461810)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffff80001046304c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffff8000104646b4)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffff800010475d7c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffff80001047a11c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffff80001048069c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffff80001048bda4)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffff800010494670)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffff80001049911c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffff8000104a1a94)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffff8000104a8d5c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffff8000104bdd18)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffff8000104c266c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (c0621588)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (c0621cc8)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (c0623858)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c0624934)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (c0637694)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (c063b988)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (c064471c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (c064da40)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (c0656060)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (c065aa94)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c0663c58)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (c066b248)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (c0681554)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (c06865a4)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (c00000000057d3c0)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (c00000000057de58)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (c0000000005800a8)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c0000000005816f0)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (c000000000597ad8)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (c00000000059c358)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (c0000000005a8234)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (c0000000005b2c00)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (c0000000005bdaa0)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (c0000000005c3290)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c0000000005ce5ec)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (c0000000005d6a10)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (c0000000005f4044)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (c0000000005f9668)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffe0002f010e)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffe0002f07de)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffe0002f1c52)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffe0002f28a4)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffe0003016e8)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffe00030434e)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffe00030baa8)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffe000311e6e)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffe000319308)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffe00031cc72)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffe0003239e2)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffe0003290ce)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffe00033983c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffe00033df3e)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff81386fd2)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff813875f6)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff81388dbf)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138a0d1)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff8139acb9)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8139edd7)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a6e80)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813aebbc)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff813b6036)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffff813b9f12)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c24e7)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff813c88a8)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813dce0c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813e1cc5)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff81377a62)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff81378086)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff8137984f)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8137ab61)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff8138b749)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8138f867)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff81397910)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff8139f64c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff813a6ac6)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffff813aa9a2)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813b2f77)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff813b9328)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813cd88c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813d2745)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff81384aa2)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff813850c6)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff8138671f)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81387a31)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81398519)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8139c637)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813a46e0)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813ac41c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff813b3896)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffff813b7772)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813bf997)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff813c5d38)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813da2ac)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813df045)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
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
In fs/ext4/balloc.c (ffffffff8139861d)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/bitmap.c (ffffffff81398c46)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/dir.c (ffffffff8139a40c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139b711)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff813ac8f1)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813b0b4a)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/inode.c (ffffffff813b8ded)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
```
```
In fs/ext4/ioctl.c (ffffffff813c0dbc)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_group_add
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mballoc.c (ffffffff813c8442)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_add_groupinfo
```
```
In fs/ext4/mmp.c (ffffffff813cc475)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813d4a77)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/resize.c (ffffffff813daf68)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_setup_new_descs
  - fs/ext4/resize.c:ext4_setup_new_descs
```
```
In fs/ext4/super.c (ffffffff813ef58c)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum_set
  - fs/ext4/super.c:ext4_group_desc_csum_verify
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813f4465)
Location: fs/ext4/ext4.h:1812
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
</details>
</li>
</ul>

## Differences
