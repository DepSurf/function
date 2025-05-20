# Function: <code>sb_bread</code>

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
In fs/ext4/resize.c (ffffffff812bf4f5)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_fs
```
```
In fs/ext4/migrate.c (ffffffff812cc1db)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/indirect.c (ffffffff812d8d21)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/xattr.c (ffffffff812dcf2e)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
```
```
In fs/fat/dir.c (ffffffff812f5ff0)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff812f95f7)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff812fb95c)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/fat/misc.c (ffffffff812fe219)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff812fe82b)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/resize.c (ffffffff812f126c)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/migrate.c (ffffffff812fc240)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/indirect.c (ffffffff81308aa9)
Location: include/linux/buffer_head.h:299
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff8130eff5)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/squashfs/block.c (ffffffff81320cac)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81329638)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8132d227)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff81330dcb)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81332219)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81332837)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/resize.c (ffffffff8130723c)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/migrate.c (ffffffff813121f0)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/indirect.c (ffffffff8131eab9)
Location: include/linux/buffer_head.h:302
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81324e15)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/squashfs/block.c (ffffffff81336b5c)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff8133f378)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81342f67)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff81346b1b)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81347fb9)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813485d7)
Location: include/linux/buffer_head.h:302
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff812f76b3)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/migrate.c (ffffffff81313ca4)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/resize.c (ffffffff81321d0c)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/xattr.c (ffffffff8133ebc2)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/squashfs/block.c (ffffffff8134b92e)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81353ea6)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813579f7)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff8135b5b5)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8135c9c9)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8135d145)
Location: include/linux/buffer_head.h:303
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff8131bcf3)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/migrate.c (ffffffff81338464)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/resize.c (ffffffff8134644c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/xattr.c (ffffffff813631a2)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/squashfs/block.c (ffffffff8136ff70)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81378ac6)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8137c4dc)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff813802b8)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813816c9)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81381e45)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff81349bf0)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/migrate.c (ffffffff81366a18)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
```
```
In fs/ext4/resize.c (ffffffff813742ff)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
```
```
In fs/ext4/xattr.c (ffffffff813918cf)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/squashfs/block.c (ffffffff8139e68b)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813a764e)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813aae78)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff813ae9c8)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813b02b9)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813b0c08)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff81361db0)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffff8138c73f)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffffffff813b7409)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813c043d)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813c3bf8)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff813c7bc6)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813c9919)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813ca308)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff8138b244)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffff813b6e46)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffffffff813e1b8b)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813eac5a)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813ee4bd)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff813f277c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813f44b7)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813f4e76)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff813a3c94)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffff813cfd6c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffffffff813fbbbb)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff81404cfa)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814085f4)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff8140c682)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8140e387)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8140ed46)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff813efee6)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffff8141c9b0)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/fat/dir.c (ffffffff81452b39)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814561a9)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff8145a5b8)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8145c167)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8145c82f)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/fat/dir.c (ffffffff8146efe9)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81472569)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff81476908)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81478067)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8147855f)
Location: include/linux/buffer_head.h:299
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/fat/dir.c (ffffffff814745f6)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81477f79)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff8147c378)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8147daf7)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8147dfcf)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/dir.c (ffffffff814cb322)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814cf0f9)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff814d3a78)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff814d5377)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff814d576f)
Location: include/linux/buffer_head.h:301
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/dir.c (ffffffff81557404)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8155bbe8)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff81560cbd)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff815623ab)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81562887)
Location: include/linux/buffer_head.h:323
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/dir.c (ffffffff815f8fd3)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff815fda58)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff81602f7f)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81604cfb)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81605285)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/dir.c (ffffffff81630f33)
Location: include/linux/buffer_head.h:349
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81635a08)
Location: include/linux/buffer_head.h:349
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff8163ae9f)
Location: include/linux/buffer_head.h:349
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8163cc0b)
Location: include/linux/buffer_head.h:349
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8163d195)
Location: include/linux/buffer_head.h:349
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/dir.c (ffffffff8166a3e3)
Location: include/linux/buffer_head.h:319
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8166eee8)
Location: include/linux/buffer_head.h:319
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff816743fe)
Location: include/linux/buffer_head.h:319
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff8167617b)
Location: include/linux/buffer_head.h:319
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81676705)
Location: include/linux/buffer_head.h:319
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/ext4/indirect.c (ffff800010477310)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffff8000104a876c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffff8000104d98b4)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffff8000104e39cc)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffff8000104e8920)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffff8000104ed44c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffff8000104eeee8)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffff8000104efbd4)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (c0638ea8)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (c066ab0c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (c069b074)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (c06a2c18)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (c06a6ae4)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (c06ab094)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (c06aca34)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (c06ad1d8)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (c000000000599508)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (c0000000005d64e0)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (c0000000006141d0)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (c000000000620bec)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (c00000000062633c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (c00000000062c138)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (c00000000062e080)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (c00000000062eac0)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffe000302702)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffe000328cd2)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffffffe00034ea5a)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffe000356fba)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffe000359d54)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffe00035d924)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffe00035efb8)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffe00035f9c6)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff8139c274)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffff813c834c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffffffff813f419b)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813fd2da)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81400bd4)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff81404c62)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81406967)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81407326)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff8138cd04)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffff813b8dcc)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffffffff813e4c1b)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813edd5a)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813f1654)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff813f56e2)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff813f73e7)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff813f7da6)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff81399ad4)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffff813c57dc)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffffffff813f151b)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff813fa65a)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff813fdf54)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff81401fe2)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81403ce7)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff814046a6)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
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
In fs/ext4/indirect.c (ffffffff813adbc4)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_free_branches
```
```
In fs/ext4/resize.c (ffffffff813daa0c)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
```
```
In fs/squashfs/block.c (ffffffff8140712b)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
```
```
In fs/fat/dir.c (ffffffff814102ba)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81413c04)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
```
```
In fs/fat/inode.c (ffffffff81417fb2)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
```
```
In fs/fat/misc.c (ffffffff81419957)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8141a326)
Location: include/linux/buffer_head.h:305
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
</details>
</li>
</ul>

## Differences
