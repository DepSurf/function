# Function: <code>__ext4_warning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ba1f0)
Location: fs/ext4/super.c:625
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
```
**Symbols:**

```
ffffffff812ba1f0-ffffffff812ba2b1: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e9110)
Location: fs/ext4/super.c:654
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
```
**Symbols:**

```
ffffffff812e9110-ffffffff812e91d1: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fee50)
Location: fs/ext4/super.c:657
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
```
**Symbols:**

```
ffffffff812fee50-ffffffff812fef11: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81333c00)
Location: fs/ext4/super.c:677
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81333c00-ffffffff81333ccc: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81358110)
Location: fs/ext4/super.c:676
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81358110-ffffffff813581dc: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:682
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8138bbd1-ffffffff8138bc1b: __ext4_warning.cold.141 (STB_LOCAL)
ffffffff813862e0-ffffffff8138635e: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:724
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813a4750-ffffffff813a479a: __ext4_warning.cold.145 (STB_LOCAL)
ffffffff8139ede0-ffffffff8139ee5e: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:735
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:ext4_es_remove_blks
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813ce92e-ffffffff813ce978: __ext4_warning.cold (STB_LOCAL)
ffffffff813c9460-ffffffff813c94de: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813e7fed-ffffffff813e8037: __ext4_warning.cold (STB_LOCAL)
ffffffff813e2760-ffffffff813e27de: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:761
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
```
**Symbols:**

```
ffffffff81434b68-ffffffff81434bb2: __ext4_warning.cold (STB_LOCAL)
ffffffff8142f680-ffffffff8142f6fc: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:917
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
```
**Symbols:**

```
ffffffff81bec962-ffffffff81bec9ac: __ext4_warning.cold (STB_LOCAL)
ffffffff814483a0-ffffffff8144842a: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:926
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
```
**Symbols:**

```
ffffffff81bdea14-ffffffff81bdea5e: __ext4_warning.cold (STB_LOCAL)
ffffffff8144dbf0-ffffffff8144dc7a: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:925
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
```
**Symbols:**

```
ffffffff81ccdb93-ffffffff81ccdbdd: __ext4_warning.cold (STB_LOCAL)
ffffffff814a1c80-ffffffff814a1d0a: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:957
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
```
**Symbols:**

```
ffffffff81e80a7d-ffffffff81e80ac7: __ext4_warning.cold (STB_LOCAL)
ffffffff81528ea0-ffffffff81528f6c: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c6f70)
Location: fs/ext4/super.c:950
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
```
**Symbols:**

```
ffffffff815c6f70-ffffffff815c707d: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fecf0)
Location: fs/ext4/super.c:950
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/hash.c:__ext4fs_dirhash
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
```
**Symbols:**

```
ffffffff815fecf0-ffffffff815fedfd: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff816378f0)
Location: fs/ext4/super.c:1019
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/hash.c:__ext4fs_dirhash
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_lookup
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:reserve_backup_gdb
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all
```
**Symbols:**

```
ffffffff816378f0-ffffffff816379fd: __ext4_warning (STB_GLOBAL)
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
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bbb50)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffff8000104bbb50-ffff8000104bbc18: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067f2c4)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_reserved_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
c067f2c4-c067f37c: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f1b50)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
c0000000005f1b50-c0000000005f1c3c: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000337e46)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/indirect.c:ext4_block_to_path
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffe000337e46-ffffffe000337ecc: __ext4_warning (STB_GLOBAL)
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
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813e05cd-ffffffff813e0617: __ext4_warning.cold (STB_LOCAL)
ffffffff813dad40-ffffffff813dadbe: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813d104d-ffffffff813d1097: __ext4_warning.cold (STB_LOCAL)
ffffffff813cb7c0-ffffffff813cb83e: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813dd94d-ffffffff813dd997: __ext4_warning.cold (STB_LOCAL)
ffffffff813d81e0-ffffffff813d825e: __ext4_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ext4_warning(struct super_block *sb, const char *function, unsigned int line, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:730
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents.c:ext4_convert_unwritten_extents
  - fs/ext4/extents_status.c:es_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:__dump_mmp_msg
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:add_new_gdb
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:verify_group_input
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/resize.c:ext4_resize_begin
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_update_dynamic_rev
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813f2d79-ffffffff813f2dc3: __ext4_warning.cold (STB_LOCAL)
ffffffff813ed480-ffffffff813ed4fe: __ext4_warning (STB_GLOBAL)
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
