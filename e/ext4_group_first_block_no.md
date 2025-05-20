# Function: <code>ext4_group_first_block_no</code>

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
In fs/ext4/balloc.c (ffffffff8128f113)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In fs/ext4/super.c (ffffffff812bcda8)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812bf037)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
```
```
In fs/ext4/mballoc.c (ffffffff812cd80d)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/ext4/block_validity.c (ffffffff812d6365)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/xattr.c (ffffffff812dd960)
Location: fs/ext4/ext4.h:2044
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff812bd875)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/super.c (ffffffff812ebd4e)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff812f18b7)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81305744)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/block_validity.c (ffffffff81305ff7)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/xattr.c (ffffffff8130d2e1)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff812d2ec5)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/super.c (ffffffff81301d08)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/resize.c (ffffffff81307887)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8131b702)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/block_validity.c (ffffffff8131bfb7)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/xattr.c (ffffffff813231d6)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff812e44d5)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff812e4b84)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff812f2a3c)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff81312ae7)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813222b7)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff81339029)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff8133c4a7)
Location: fs/ext4/ext4.h:2129
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff81308f01)
Location: fs/ext4/ext4.h:2089
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff813095a7)
Location: fs/ext4/ext4.h:2089
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff81316fcc)
Location: fs/ext4/ext4.h:2089
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff813372a2)
Location: fs/ext4/ext4.h:2089
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff81346a0a)
Location: fs/ext4/ext4.h:2089
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff8135cd49)
Location: fs/ext4/ext4.h:2089
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff813609cc)
Location: fs/ext4/ext4.h:2089
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff81336e31)
Location: fs/ext4/ext4.h:2090
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff813374d8)
Location: fs/ext4/ext4.h:2090
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff81344d5c)
Location: fs/ext4/ext4.h:2090
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff813659e7)
Location: fs/ext4/ext4.h:2090
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff81374499)
Location: fs/ext4/ext4.h:2090
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff8137d82f)
Location: fs/ext4/ext4.h:2090
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff8138f299)
Location: fs/ext4/ext4.h:2090
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff8134e0b1)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff8134e758)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff8135ceac)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff8137dda7)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8138ca1f)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff81395fdf)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff813a7ce7)
Location: fs/ext4/ext4.h:2103
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff81376a65)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81377190)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff81386041)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff813a44ac)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813b70e0)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff813bff91)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff813d20a4)
Location: fs/ext4/ext4.h:2127
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff8138ecd5)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff8138f4b7)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff8139ea91)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff813bd31c)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813d006d)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff813d9261)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff813eb784)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff813da285)
Location: fs/ext4/ext4.h:2283
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
```
```
In fs/ext4/block_validity.c (ffffffff813da96a)
Location: fs/ext4/ext4.h:2283
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff813ea78e)
Location: fs/ext4/ext4.h:2283
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_sb
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff81408fff)
Location: fs/ext4/ext4.h:2283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8141cbcb)
Location: fs/ext4/ext4.h:2283
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff81426121)
Location: fs/ext4/ext4.h:2283
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff81438d16)
Location: fs/ext4/ext4.h:2283
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff813ebf56)
Location: fs/ext4/ext4.h:2408
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
```
```
In fs/ext4/block_validity.c (ffffffff813ec63d)
Location: fs/ext4/ext4.h:2408
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff813fca3e)
Location: fs/ext4/ext4.h:2408
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_sb
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff8141b51d)
Location: fs/ext4/ext4.h:2408
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff81430998)
Location: fs/ext4/ext4.h:2408
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff8143d521)
Location: fs/ext4/ext4.h:2408
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff8145183f)
Location: fs/ext4/ext4.h:2408
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff813f2485)
Location: fs/ext4/ext4.h:2460
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
```
```
In fs/ext4/block_validity.c (ffffffff813f2b7d)
Location: fs/ext4/ext4.h:2460
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff81402874)
Location: fs/ext4/ext4.h:2460
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff81421bc0)
Location: fs/ext4/ext4.h:2460
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff81437558)
Location: fs/ext4/ext4.h:2460
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff81443361)
Location: fs/ext4/ext4.h:2460
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff81456f6f)
Location: fs/ext4/ext4.h:2460
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff81444466)
Location: fs/ext4/ext4.h:2530
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
```
```
In fs/ext4/block_validity.c (ffffffff81444b66)
Location: fs/ext4/ext4.h:2530
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff81454f44)
Location: fs/ext4/ext4.h:2530
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff8147430e)
Location: fs/ext4/ext4.h:2530
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8148b1d4)
Location: fs/ext4/ext4.h:2530
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff81496fd1)
Location: fs/ext4/ext4.h:2530
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff814aafd9)
Location: fs/ext4/ext4.h:2530
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff814c0346)
Location: fs/ext4/ext4.h:2535
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
```
```
In fs/ext4/block_validity.c (ffffffff814c0b09)
Location: fs/ext4/ext4.h:2535
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff814d2784)
Location: fs/ext4/ext4.h:2535
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/ioctl.c (ffffffff814ed59b)
Location: fs/ext4/ext4.h:2535
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff814fb4e7)
Location: fs/ext4/ext4.h:2535
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff8150efec)
Location: fs/ext4/ext4.h:2535
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff815221ca)
Location: fs/ext4/ext4.h:2535
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff81532f82)
Location: fs/ext4/ext4.h:2535
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff81558396)
Location: fs/ext4/ext4.h:2545
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
```
```
In fs/ext4/block_validity.c (ffffffff81558be9)
Location: fs/ext4/ext4.h:2545
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff8156b324)
Location: fs/ext4/ext4.h:2545
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/ioctl.c (ffffffff8158740b)
Location: fs/ext4/ext4.h:2545
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff81595b5c)
Location: fs/ext4/ext4.h:2545
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff815a9e7e)
Location: fs/ext4/ext4.h:2545
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff815bec0d)
Location: fs/ext4/ext4.h:2545
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff815d1473)
Location: fs/ext4/ext4.h:2545
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff815901e2)
Location: fs/ext4/ext4.h:2539
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
```
```
In fs/ext4/block_validity.c (ffffffff81590a39)
Location: fs/ext4/ext4.h:2539
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff815a31e3)
Location: fs/ext4/ext4.h:2539
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/ioctl.c (ffffffff815bdacb)
Location: fs/ext4/ext4.h:2539
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c20d2)
Location: fs/ext4/ext4.h:2539
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff815e06de)
Location: fs/ext4/ext4.h:2539
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff815f59ad)
Location: fs/ext4/ext4.h:2539
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff81608fe9)
Location: fs/ext4/ext4.h:2539
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff815c8f22)
Location: fs/ext4/ext4.h:2557
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_num_overhead_clusters
```
```
In fs/ext4/block_validity.c (ffffffff815c9774)
Location: fs/ext4/ext4.h:2557
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff815dbf03)
Location: fs/ext4/ext4.h:2557
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/ioctl.c (ffffffff815f688b)
Location: fs/ext4/ext4.h:2557
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
```
In fs/ext4/mballoc.c (ffffffff815ff379)
Location: fs/ext4/ext4.h:2557
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_new_blocks_simple
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff81619196)
Location: fs/ext4/ext4.h:2557
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_group_extend_no_check
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffff8162e2bd)
Location: fs/ext4/ext4.h:2557
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff81641d29)
Location: fs/ext4/ext4.h:2557
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffff800010461248)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffff800010461d3c)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffff800010471fec)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffff800010493ffc)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffff8000104a8b2c)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffff8000104ac908)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffff8000104c4740)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (c06218e0)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (c0622254)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (c0633048)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (c0655678)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (c066af78)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (c0674f2c)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (c06886bc)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (c00000000057d95c)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (c00000000057e554)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (c000000000592c00)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (c0000000005bcff4)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (c0000000005d67a0)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (c0000000005e4848)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (c0000000005fc024)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffe0002f04ee)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffe0002f0c3c)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffe0002fdfd8)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffe0003189b8)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffe000328eac)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
  - fs/ext4/resize.c:ext4_alloc_group_tables
  - fs/ext4/resize.c:ext4_alloc_group_tables
```
```
In fs/ext4/super.c (ffffffe00032fcb4)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffe00033f078)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff813872b5)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81387a97)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff81397071)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff813b58fc)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813c864d)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff813d1841)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff813e3d64)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff81377d45)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81378527)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff81387b01)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff813a638c)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813b90cd)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff813c22c1)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff813d47e4)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff81384d85)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff81385567)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff813949d1)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff813b315c)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813c5add)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff813cecd1)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff813e10e4)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/balloc.c (ffffffff81398905)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_free_clusters_after_init
  - fs/ext4/balloc.c:num_clusters_in_group
```
```
In fs/ext4/block_validity.c (ffffffff813990e7)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/fsmap.c (ffffffff813a8ac1)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev_helper
```
```
In fs/ext4/mballoc.c (ffffffff813c7ca3)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:mb_free_blocks
```
```
In fs/ext4/resize.c (ffffffff813dad0d)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/resize.c:ext4_add_new_descs
  - fs/ext4/resize.c:update_backups
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:set_flexbg_block_bitmap
```
```
In fs/ext4/super.c (ffffffff813e3f21)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/super.c:descriptor_loc
```
```
In fs/ext4/xattr.c (ffffffff813f64ff)
Location: fs/ext4/ext4.h:2185
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
</ul>

## Differences
