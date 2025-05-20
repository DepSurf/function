# Function: <code>ext4_get_inode_loc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299ba0)
Location: fs/ext4/inode.c:4019
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data
```
**Symbols:**

```
ffffffff81299ba0-ffffffff81299bbf: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c91b3)
Location: fs/ext4/inode.c:4327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
**Symbols:**

```
ffffffff812c7280-ffffffff812c72a1: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dedf3)
Location: fs/ext4/inode.c:4456
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
```
**Symbols:**

```
ffffffff812dcd80-ffffffff812dcda1: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81302e6f)
Location: fs/ext4/inode.c:4580
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff81301610-ffffffff81301631: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8132785f)
Location: fs/ext4/inode.c:4629
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_try_to_evict_inline_data
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff81325fb0-ffffffff81325fd1: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81355503)
Location: fs/ext4/inode.c:4678
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff81354360-ffffffff81354381: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136d833)
Location: fs/ext4/inode.c:4708
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8136c5d0-ffffffff8136c5f1: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396e38)
Location: fs/ext4/inode.c:4720
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff81395b90-ffffffff81395bb4: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813af868)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813ae560-ffffffff813ae584: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fb8a8)
Location: fs/ext4/inode.c:4409
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813fa580-ffffffff813fa5a4: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140cb50)
Location: fs/ext4/inode.c:4451
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
**Symbols:**

```
ffffffff8140cb50-ffffffff8140cbe5: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412cd0)
Location: fs/ext4/inode.c:4450
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
**Symbols:**

```
ffffffff81412cd0-ffffffff81412d65: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81466000)
Location: fs/ext4/inode.c:4371
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
**Symbols:**

```
ffffffff81466000-ffffffff8146609d: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e5ab0)
Location: fs/ext4/inode.c:4593
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
**Symbols:**

```
ffffffff814e5ab0-ffffffff814e5b4d: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157f1f0)
Location: fs/ext4/inode.c:4688
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
**Symbols:**

```
ffffffff8157f1f0-ffffffff8157f28d: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b66a0)
Location: fs/ext4/inode.c:4473
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_folio
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
**Symbols:**

```
ffffffff815b66a0-ffffffff815b673d: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ef440)
Location: fs/ext4/inode.c:4492
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_iomap_xattr_begin
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_link
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_folio
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/inline.c:ext4_get_max_inline_size
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/fast_commit.c:ext4_fc_write_inode
```
**Symbols:**

```
ffffffff815ef440-ffffffff815ef4dd: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104842d4)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffff8000104830d8-ffff80001048311c: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c064590c)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
c06444b0-c06444d8: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a946c)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
c0000000005a7eb0-c0000000005a7ed4: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030c7ba)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffe00030b7f0-ffffffe00030b82e: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a7e48)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813a6b40-ffffffff813a6b64: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813988d8)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813975d0-ffffffff813975f4: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a56a8)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813a43a0-ffffffff813a43c4: ext4_get_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b9de8)
Location: fs/ext4/inode.c:4709
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
Direct callers:
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_create_inline_dir
  - fs/ext4/inline.c:ext4_get_first_inline_block
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inline.c:ext4_find_inline_data_nolock
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813b8aa0-ffffffff813b8ac4: ext4_get_inode_loc (STB_GLOBAL)
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
