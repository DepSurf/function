# Function: <code>__bread_gfp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244b80)
Location: fs/buffer.c:1428
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81244b80-ffffffff81244c51: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126d740)
Location: fs/buffer.c:1418
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8126d740-ffffffff8126d816: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81280990)
Location: fs/buffer.c:1418
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81280990-ffffffff81280a66: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128e250)
Location: fs/buffer.c:1413
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8128e250-ffffffff8128e326: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b0e60)
Location: fs/buffer.c:1373
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812b0e60-ffffffff812b0f36: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d8cd0)
Location: fs/buffer.c:1344
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812d8cd0-ffffffff812d8da1: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ee1a0)
Location: fs/buffer.c:1352
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812ee1a0-ffffffff812ee271: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130f960)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8130f960-ffffffff8130fa49: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813228e0)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813228e0-ffffffff813229c9: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135cb50)
Location: fs/buffer.c:1397
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8135cb50-ffffffff8135cc9b: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136aeb0)
Location: fs/buffer.c:1396
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_rebuild_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8136aeb0-ffffffff8136affb: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81371440)
Location: fs/buffer.c:1401
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81371440-ffffffff81371533: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813c0ba0)
Location: fs/buffer.c:1376
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff813c0ba0-ffffffff813c0cb1: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81445ba0)
Location: fs/buffer.c:1375
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81445ba0-ffffffff81445cbc: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d5330)
Location: fs/buffer.c:1364
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff814d5330-ffffffff814d5442: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150c8c0)
Location: fs/buffer.c:1476
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff8150c8c0-ffffffff8150ca29: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81541510)
Location: fs/buffer.c:1461
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_rebuild_parent
```
**Symbols:**

```
ffffffff81541510-ffffffff81541692: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103db828)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffff8000103db828-ffff8000103db9cc: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b4bb4)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
c05b4bb4-c05b4d44: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e0b80)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
c0000000004e0b80-c0000000004e0d80: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000293f3c)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffe000293f3c-ffffffe00029406a: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131aec0)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8131aec0-ffffffff8131afa9: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130ba60)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8130ba60-ffffffff8130bb49: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318990)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81318990-ffffffff81318a79: __bread_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *__bread_gfp(struct block_device *bdev, sector_t block, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132a5d0)
Location: fs/buffer.c:1353
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/fat/dir.c:fat__get_entry
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/fatent.c:fat12_ent_bread
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:fat_set_state
  - fs/fat/misc.c:fat_clusters_flush
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8132a5d0-ffffffff8132a69d: __bread_gfp (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
