# Function: <code>ext4_sb_bread</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139c200)
Location: fs/ext4/super.c:155
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff8139c200-ffffffff8139c2b1: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c6460)
Location: fs/ext4/super.c:156
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813c6460-ffffffff813c6516: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813df820)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813df820-ffffffff813df8d6: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142c160)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_block_list
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff8142c160-ffffffff8142c238: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81444fb0)
Location: fs/ext4/super.c:234
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_block_list
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff81444fb0-ffffffff81444fd9: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144a8d0)
Location: fs/ext4/super.c:234
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff8144a8d0-ffffffff8144a8f9: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149e380)
Location: fs/ext4/super.c:231
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff8149e380-ffffffff8149e3a9: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81524990)
Location: fs/ext4/super.c:250
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff81524990-ffffffff815249c8: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c1e10)
Location: fs/ext4/super.c:243
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff815c1e10-ffffffff815c1e48: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f9590)
Location: fs/ext4/super.c:243
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff815f9590-ffffffff815f95c8: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, blk_opf_t op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81632120)
Location: fs/ext4/super.c:244
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff81632120-ffffffff81632166: ext4_sb_bread (STB_GLOBAL)
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
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b8558)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffff8000104b8558-ffff8000104b8654: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067bdf8)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
c067bdf8-c067beec: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ed6f0)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
c0000000005ed6f0-c0000000005ed818: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000335090)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffe000335090-ffffffe000335146: ext4_sb_bread (STB_GLOBAL)
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
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d7e00)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813d7e00-ffffffff813d7eb6: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c8880)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813c8880-ffffffff813c8936: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d5290)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813d5290-ffffffff813d5346: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_sb_bread(struct super_block *sb, sector_t block, int op_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ea520)
Location: fs/ext4/super.c:151
Inline: False
Direct callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:update_dind_extent_range
  - fs/ext4/migrate.c:update_ind_extent_range
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813ea520-ffffffff813ea5cd: ext4_sb_bread (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int op_flags</code> ➡️ <code>blk_opf_t op_flags</code>
</li>
</ul>
</details>
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
