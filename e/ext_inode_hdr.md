# Function: <code>ext_inode_hdr</code>

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
In fs/ext4/extents.c (ffffffff812c3b4e)
Location: fs/ext4/ext4_extents.h:176
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:176
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
In fs/ext4/extents.c (ffffffff812f5fda)
Location: fs/ext4/ext4_extents.h:176
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_check_inode
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
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
In fs/ext4/extents.c (ffffffff8130bf8a)
Location: fs/ext4/ext4_extents.h:176
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_check_inode
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
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
In fs/ext4/extents.c (ffffffff812eae67)
Location: fs/ext4/ext4_extents.h:176
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_check_inode
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
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
In fs/ext4/extents.c (ffffffff8130f90a)
Location: fs/ext4/ext4_extents.h:176
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_check_inode
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:176
Inline: True
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
In fs/ext4/extents.c (ffffffff81340dec)
Location: fs/ext4/ext4_extents.h:165
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffff81366ed1)
Location: fs/ext4/ext4_extents.h:165
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81368be2)
Location: fs/ext4/ext4_extents.h:165
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff81359561)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffff8137f345)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81381102)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff813824f0)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffff813a87ad)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813aa42d)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff8139aaa0)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffff813c16b5)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813c335d)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff813e5f54)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_ext_determine_hole
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff8140d9a4)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8140f6fb)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff813f7774)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_ext_determine_hole
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff81420e04)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff81422bbb)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff813fdc04)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff814275c4)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff814293bb)
Location: fs/ext4/ext4_extents.h:181
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff8144fec2)
Location: fs/ext4/ext4_extents.h:182
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_valid_extent_entries
  - fs/ext4/extents.c:ext4_valid_extent_entries
```
```
In fs/ext4/migrate.c (ffffffff8147b241)
Location: fs/ext4/ext4_extents.h:182
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff8147d1bc)
Location: fs/ext4/ext4_extents.h:182
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff814ca8ce)
Location: fs/ext4/ext4_extents.h:182
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_check_inode
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:182
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:182
Inline: True
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
In fs/ext4/extents.c (ffffffff81562fba)
Location: fs/ext4/ext4_extents.h:182
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_check_inode
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:182
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:182
Inline: True
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
In fs/ext4/extents.c (ffffffff8159aced)
Location: fs/ext4/ext4_extents.h:182
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_check_inode
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:182
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:182
Inline: True
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
In fs/ext4/extents.c (ffffffff815d3b2d)
Location: fs/ext4/ext4_extents.h:182
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:ext4_ext_check_inode
```
```
In fs/ext4/migrate.c (0)
Location: fs/ext4/ext4_extents.h:182
Inline: True
```
```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/ext4_extents.h:182
Inline: True
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
In fs/ext4/extents.c (ffff80001046d390)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffff800010498b64)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffff80001049abd8)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (c062ea60)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (c065a768)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (c065c744)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (c00000000058d224)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (c0000000005c2f20)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (c0000000005c5550)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffe0002fa76e)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffe00031ca62)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffe00031e2f0)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff81393080)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffff813b9c95)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813bb93d)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff81383b10)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffff813aa725)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813ac3cd)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff813909e0)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffff813b74f5)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813b919d)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff813a4870)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_calc_credits_for_single_extent
  - fs/ext4/extents.c:ext4_fill_fiemap_extents
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge_right
  - fs/ext4/extents.c:ext4_ext_correct_indexes
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_tree_init
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:ext4_ext_check_inode
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:ext4_ext_calc_metadata_amount
```
```
In fs/ext4/migrate.c (ffffffff813cc205)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ind_migrate
```
```
In fs/ext4/move_extent.c (ffffffff813cdebd)
Location: fs/ext4/ext4_extents.h:178
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
</details>
</li>
</ul>

## Differences
