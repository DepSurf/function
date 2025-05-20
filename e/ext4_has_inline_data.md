# Function: <code>ext4_has_inline_data</code>

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
In fs/ext4/dir.c (ffffffff8129096f)
Location: fs/ext4/ext4.h:3026
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inode.c (ffffffff81295e53)
Location: fs/ext4/ext4.h:3026
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
```
```
In fs/ext4/namei.c (ffffffff812a2a89)
Location: fs/ext4/ext4.h:3026
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_empty_dir
```
```
In fs/ext4/extents.c (ffffffff812c66b5)
Location: fs/ext4/ext4.h:3026
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
```
```
In fs/ext4/xattr.c (ffffffff812de477)
Location: fs/ext4/ext4.h:3026
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:ext4_xattr_set
```
```
In fs/ext4/inline.c (ffffffff812e0470)
Location: fs/ext4/ext4.h:3026
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
```
```
In fs/ext4/acl.c (ffffffff812e44d4)
Location: fs/ext4/ext4.h:3026
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
```
```
In fs/ext4/crypto_policy.c (ffffffff812e4910)
Location: fs/ext4/ext4.h:3026
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_process_policy
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
In fs/ext4/dir.c (ffffffff812be2c1)
Location: fs/ext4/ext4.h:3063
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inode.c (ffffffff812c887e)
Location: fs/ext4/ext4.h:3063
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/namei.c (ffffffff812d19c9)
Location: fs/ext4/ext4.h:3063
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/super.c (ffffffff812e73ec)
Location: fs/ext4/ext4.h:3063
Inline: True
```
```
In fs/ext4/extents.c (ffffffff812f9201)
Location: fs/ext4/ext4.h:3063
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
```
```
In fs/ext4/xattr.c (ffffffff8130e6f5)
Location: fs/ext4/ext4.h:3063
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/inline.c (ffffffff81312b46)
Location: fs/ext4/ext4.h:3063
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/acl.c (ffffffff813143eb)
Location: fs/ext4/ext4.h:3063
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/dir.c (ffffffff812d390d)
Location: fs/ext4/ext4.h:3041
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inode.c (ffffffff812de44e)
Location: fs/ext4/ext4.h:3041
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/namei.c (ffffffff812e7749)
Location: fs/ext4/ext4.h:3041
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/super.c (ffffffff812fd097)
Location: fs/ext4/ext4.h:3041
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_set_context
```
```
In fs/ext4/extents.c (ffffffff8130f201)
Location: fs/ext4/ext4.h:3041
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
```
```
In fs/ext4/xattr.c (ffffffff81324435)
Location: fs/ext4/ext4.h:3041
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
```
```
In fs/ext4/inline.c (ffffffff81328ac8)
Location: fs/ext4/ext4.h:3041
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/acl.c (ffffffff8132a3cb)
Location: fs/ext4/ext4.h:3041
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_set_acl
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
In fs/ext4/dir.c (ffffffff812e52e6)
Location: fs/ext4/ext4.h:3058
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff812ed751)
Location: fs/ext4/ext4.h:3058
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/inline.c (ffffffff812fcaa8)
Location: fs/ext4/ext4.h:3058
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81302553)
Location: fs/ext4/ext4.h:3058
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff813170c9)
Location: fs/ext4/ext4.h:3058
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff8133da14)
Location: fs/ext4/ext4.h:3058
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81309d16)
Location: fs/ext4/ext4.h:3019
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81312211)
Location: fs/ext4/ext4.h:3019
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/inline.c (ffffffff81321308)
Location: fs/ext4/ext4.h:3019
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81326ee3)
Location: fs/ext4/ext4.h:3019
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff8133b939)
Location: fs/ext4/ext4.h:3019
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff81361ff4)
Location: fs/ext4/ext4.h:3019
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_inline_set
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81337c86)
Location: fs/ext4/ext4.h:3025
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff813400c1)
Location: fs/ext4/ext4.h:3025
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/inline.c (ffffffff8134f318)
Location: fs/ext4/ext4.h:3025
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8135530c)
Location: fs/ext4/ext4.h:3025
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/namei.c (ffffffff8136a009)
Location: fs/ext4/ext4.h:3025
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff813905f8)
Location: fs/ext4/ext4.h:3025
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff8134ef06)
Location: fs/ext4/ext4.h:3052
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff813576a1)
Location: fs/ext4/ext4.h:3052
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/inline.c (ffffffff813674c8)
Location: fs/ext4/ext4.h:3052
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8136d63c)
Location: fs/ext4/ext4.h:3052
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff81374757)
Location: fs/ext4/ext4.h:3052
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff813824c9)
Location: fs/ext4/ext4.h:3052
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff813a91d8)
Location: fs/ext4/ext4.h:3052
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81377f55)
Location: fs/ext4/ext4.h:3136
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff81381011)
Location: fs/ext4/ext4.h:3136
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff81390898)
Location: fs/ext4/ext4.h:3136
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81396c3c)
Location: fs/ext4/ext4.h:3136
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff8139d245)
Location: fs/ext4/ext4.h:3136
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff813ab709)
Location: fs/ext4/ext4.h:3136
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff813d344c)
Location: fs/ext4/ext4.h:3136
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff813902f5)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff8139975c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff813a92f8)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813af66c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff813b5cb5)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff813c4639)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff813ecb2c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff813db8dd)
Location: fs/ext4/ext4.h:3309
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff813e5738)
Location: fs/ext4/ext4.h:3309
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813e96e3)
Location: fs/ext4/ext4.h:3309
Inline: True
```
```
In fs/ext4/inline.c (ffffffff813f52fe)
Location: fs/ext4/ext4.h:3309
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813fb6fc)
Location: fs/ext4/ext4.h:3309
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff81401695)
Location: fs/ext4/ext4.h:3309
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff81410da9)
Location: fs/ext4/ext4.h:3309
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff814399f9)
Location: fs/ext4/ext4.h:3309
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff813ed322)
Location: fs/ext4/ext4.h:3500
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff813f6f58)
Location: fs/ext4/ext4.h:3500
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813fb393)
Location: fs/ext4/ext4.h:3500
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81407a9e)
Location: fs/ext4/ext4.h:3500
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8140de5c)
Location: fs/ext4/ext4.h:3500
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff81414085)
Location: fs/ext4/ext4.h:3500
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff81424269)
Location: fs/ext4/ext4.h:3500
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff8145250c)
Location: fs/ext4/ext4.h:3500
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff813f3985)
Location: fs/ext4/ext4.h:3565
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff813fd307)
Location: fs/ext4/ext4.h:3565
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81401863)
Location: fs/ext4/ext4.h:3565
Inline: True
```
```
In fs/ext4/inline.c (ffffffff8140df0e)
Location: fs/ext4/ext4.h:3565
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff8141401c)
Location: fs/ext4/ext4.h:3565
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff8141a2f4)
Location: fs/ext4/ext4.h:3565
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff8142ac79)
Location: fs/ext4/ext4.h:3565
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff81457e98)
Location: fs/ext4/ext4.h:3565
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81445a48)
Location: fs/ext4/ext4.h:3633
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff8144f6ea)
Location: fs/ext4/ext4.h:3633
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81453df3)
Location: fs/ext4/ext4.h:3633
Inline: True
```
```
In fs/ext4/inline.c (ffffffff81460dce)
Location: fs/ext4/ext4.h:3633
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81467372)
Location: fs/ext4/ext4.h:3633
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_readpage
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff8146d4e8)
Location: fs/ext4/ext4.h:3633
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff8147ec59)
Location: fs/ext4/ext4.h:3633
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff814abf7d)
Location: fs/ext4/ext4.h:3633
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff814c1a8c)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff814cc53a)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814d1788)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_supported
```
```
In fs/ext4/inline.c (ffffffff814df6e7)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814e6f52)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/ioctl.c (ffffffff814eddaa)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff81506a39)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/symlink.c (ffffffff8152e9c5)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff81533e6a)
Location: fs/ext4/ext4.h:3595
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81559d43)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff81564c4a)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff81578827)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff815808f2)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/ioctl.c (ffffffff81587c71)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81597819)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815a1529)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/symlink.c (ffffffff815ccb25)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff815d232a)
Location: fs/ext4/ext4.h:3607
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81591b6a)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff8159d155)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff815afdc7)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815b7ea2)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/ioctl.c (ffffffff815be4f1)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff815ce23b)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff815d7ea9)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/symlink.c (ffffffff81604615)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff8160b016)
Location: fs/ext4/ext4.h:3580
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff815ca8da)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff815d5da5)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_clu_mapped
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff815e8b77)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_folio
```
```
In fs/ext4/inode.c (ffffffff815f0c42)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_dio_alignment
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readahead
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_inode_is_fast_symlink
```
```
In fs/ext4/ioctl.c (ffffffff815f72aa)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81606abb)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/namei.c (ffffffff81610519)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/symlink.c (ffffffff8163d2e5)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ext4/xattr.c (ffffffff81643dd6)
Location: fs/ext4/ext4.h:3598
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffff800010462c00)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffff80001046c158)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffff80001047cbc4)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffff800010484004)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffff80001048a6b8)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffff80001049c164)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffff8000104c5a08)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (c0622e20)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (c062d348)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (c063e69c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c064563c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (c064c928)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (c065de84)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (c0689ab8)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (c00000000057f55c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (c00000000058b988)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (c0000000005a0718)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (c0000000005a9174)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (c0000000005b1a68)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (c0000000005c6fe8)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (c0000000005fd948)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffe0002f15c4)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffe0002f9746)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffe000306a92)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffe00030c588)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffe000311aa6)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffe00031f368)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffe0003400fe)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff813888d5)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff81391d3c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff813a18d8)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a7c4c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff813ae295)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff813bcc19)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff813e510c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81379365)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff813827cc)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff81392368)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813986dc)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff8139ed25)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff813ad6a9)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff813d5b8c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81386235)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff8138f69c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff8139f138)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813a54ac)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff813abaf5)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff813ba5f9)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff813e248c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
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
In fs/ext4/dir.c (ffffffff81399f25)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:is_dx_dir
```
```
In fs/ext4/extents.c (ffffffff813a34bc)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:ext4_get_es_cache
  - fs/ext4/extents.c:_ext4_fiemap
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff813b36a8)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_inline_data_fiemap
  - fs/ext4/inline.c:ext4_inline_data_iomap
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813b9bec)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_file_getattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_set_inode_flags
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_readpages
  - fs/ext4/inode.c:ext4_bmap
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/ext4/ioctl.c (ffffffff813c0495)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/namei.c (ffffffff813cf199)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
```
In fs/ext4/xattr.c (ffffffff813f789c)
Location: fs/ext4/ext4.h:3198
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_set_credits
```
</details>
</li>
</ul>

## Differences
