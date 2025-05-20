# Function: <code>ext4_free_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d4610)
Location: fs/ext4/mballoc.c:4654
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812d4610-ffffffff812d51bd: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813042e0)
Location: fs/ext4/mballoc.c:4661
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813042e0-ffffffff81304e7c: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8131a2a0)
Location: fs/ext4/mballoc.c:4668
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8131a2a0-ffffffff8131ae47: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813116b0)
Location: fs/ext4/mballoc.c:4733
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813116b0-ffffffff81312206: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81335f20)
Location: fs/ext4/mballoc.c:4733
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81335f20-ffffffff813369c4: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81364590)
Location: fs/ext4/mballoc.c:4703
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81364590-ffffffff81364fdc: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137c840)
Location: fs/ext4/mballoc.c:4702
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8137c840-ffffffff8137d393: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a64c0)
Location: fs/ext4/mballoc.c:4704
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813a64c0-ffffffff813a6f5e: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813bf330)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813bf330-ffffffff813bfde1: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8140b3c0)
Location: fs/ext4/mballoc.c:4968
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_splice_branch
  - fs/ext4/indirect.c:ext4_splice_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8140b3c0-ffffffff8140bec2: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141e830)
Location: fs/ext4/mballoc.c:5249
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_splice_branch
  - fs/ext4/indirect.c:ext4_splice_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_tind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8141e830-ffffffff8141f2f6: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81425280)
Location: fs/ext4/mballoc.c:5782
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81425280-ffffffff81425c33: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:5857
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81ccc4c0-ffffffff81ccc5f5: ext4_free_blocks.cold (STB_LOCAL)
ffffffff81478ea0-ffffffff81479808: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814fb6c0)
Location: fs/ext4/mballoc.c:6115
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff814fb6c0-ffffffff814fb9b7: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81595e90)
Location: fs/ext4/mballoc.c:6084
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81595e90-ffffffff81596187: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6659
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff820ef5a2-ffffffff820ef5c2: ext4_free_blocks.cold (STB_LOCAL)
ffffffff815cc850-ffffffff815ccb58: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6541
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_convert_meta_bg
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff821cc6b6-ffffffff821cc6d6: ext4_free_blocks.cold (STB_LOCAL)
ffffffff816052e0-ffffffff81605623: ext4_free_blocks (STB_GLOBAL)
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
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff800010496050)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffff800010496050-ffff8000104969e4: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0657ce8)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c0657ce8-c06589e4: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005bfe40)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c0000000005bfe40-c0000000005c0bd4: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe00031ab56)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffe00031ab56-ffffffe00031b4ac: ext4_free_blocks (STB_GLOBAL)
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
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b7910)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813b7910-ffffffff813b83c1: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a83a0)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813a83a0-ffffffff813a8e51: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b5170)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813b5170-ffffffff813b5c21: ext4_free_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_free_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block, long unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c9de0)
Location: fs/ext4/mballoc.c:4723
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_split
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:free_ext_idx
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/migrate.c:free_dind_blocks
  - fs/ext4/resize.c:ext4_resize_fs
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813c9de0-ffffffff813ca91c: ext4_free_blocks (STB_GLOBAL)
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
