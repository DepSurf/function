# Function: <code>set_buffer_verified</code>

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
In fs/ext4/balloc.c (ffffffff8128f09f)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81290ea5)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff812936d5)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/namei.c (ffffffff812a1e8a)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_mkdir
```
```
In fs/ext4/extents.c (ffffffff812c2cce)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/xattr.c (ffffffff812dcfaa)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
```
In fs/ext4/inline.c (ffffffff812e002d)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/journal.c (ffffffff812f10bd)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff812bc5d1)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff812be41d)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff812c0ca9)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/namei.c (ffffffff812d5da8)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/extents.c (ffffffff812f26d2)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/xattr.c (ffffffff8130ee05)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/ext4/inline.c (ffffffff8130fceb)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/journal.c (ffffffff8131e8af)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff812d1c21)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff812d3a72)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff812d62d9)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/namei.c (ffffffff812ebaa8)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/extents.c (ffffffff813086a2)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/xattr.c (ffffffff81324c57)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/ext4/inline.c (ffffffff81325b53)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/jbd2/journal.c (ffffffff8133492f)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff812e32d7)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff812e5447)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff812e6e2e)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff812f45b8)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff812f9b7d)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff8131b793)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff8133ec39)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff81349683)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff81307cc7)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81309e6a)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8130b82e)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81318cff)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8131e1bd)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff8133fdcb)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff81363219)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff8136dcd3)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff81336c90)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff81337df8)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81339990)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81346be6)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8134c197)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff8136dda4)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff81391b08)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff8139c390)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff8134df10)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff8134f078)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81350b30)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8135ed96)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813642dc)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff81386224)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813aa65e)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff813b5150)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff813768b4)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff813780c7)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813797dd)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81387feb)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8138de2f)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff813b0045)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813d4938)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff813df813)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff8138eb24)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff81390467)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81391cfd)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813a09b0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813a688f)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff813c9005)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813ee018)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff813f98d3)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff813d9fd8)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff813dba11)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813de550)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813ecda4)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813f1a4f)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/namei.c (ffffffff81412347)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff8143b011)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_block_list
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
```
In fs/jbd2/journal.c (ffffffff814471b8)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff813ebc8f)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff813ed493)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813efe20)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813fefaf)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff814040ef)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/namei.c (ffffffff8142826c)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff81453b8d)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_block_list
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
```
In fs/jbd2/journal.c (ffffffff81463718)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff813f21cf)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff813f3afa)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813f60af)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8140519e)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8140a5ce)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/namei.c (ffffffff8142ed74)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff814594b4)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
```
In fs/jbd2/journal.c (ffffffff81468866)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff814441af)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff81445bd2)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8144842a)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff814579b0)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8145d1de)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/namei.c (ffffffff81483514)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff814ad5d1)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
```
In fs/jbd2/journal.c (ffffffff814be316)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff814c0098)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff814c1c01)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff814c4973)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff814d56f1)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff814db9f8)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/namei.c (ffffffff8150669b)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff81535621)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
```
In fs/jbd2/journal.c (ffffffff81549ae5)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff815580eb)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81559eb3)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8155cebb)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff8156e467)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff81574950)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/namei.c (ffffffff815a116b)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff815cf87a)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_check_block
```
```
In fs/jbd2/journal.c (ffffffff815e9087)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff8158fe35)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81591cdc)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81594cdb)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff815a6327)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff815ac818)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/namei.c (ffffffff815d7aeb)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff81607285)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/jbd2/journal.c (ffffffff81620824)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff815c89c4)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff815caa4c)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff815cd98b)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_dirty
```
```
In fs/ext4/ialloc.c (ffffffff815df1a6)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff815e55a8)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
```
```
In fs/ext4/namei.c (ffffffff8161015b)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff8163ffc5)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/xattr.c:check_xattrs
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
In fs/ext4/balloc.c (ffff800010460aa0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffff800010462d50)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffff800010465510)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff800010474114)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffff80001047a1ac)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffff8000104a0c44)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffff8000104c6fe0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffff8000104d5fd0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (c06214e0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (c0622fe4)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c0624ba0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c06355b8)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (c063ba50)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (c0662d50)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (c068afec)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (c0697a24)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (c00000000057d684)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (c00000000057f710)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c000000000581990)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c0000000005954e4)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (c00000000059c3e4)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (c0000000005cd284)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (c0000000005ff534)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (c000000000610b98)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffe0002f02c0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffe0002f16ec)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffe0002f2ae4)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffe0002ffb70)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffe0003043ac)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffe000322e0c)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffe00034129c)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffe00034c43c)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff81387104)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff81388a47)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138a2dd)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81398f90)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8139ee6f)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff813c15e5)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813e65f8)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff813f1eb3)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff81377b94)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff813794d7)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8137ad6d)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81389a20)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8138f8ff)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff813b2075)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813d7078)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff813e2933)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff81384bd4)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff813863a7)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81387c3d)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813967f0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff8139c6cf)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff813bea95)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813e3978)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff813ef233)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
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
In fs/ext4/balloc.c (ffffffff81398760)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (ffffffff8139a08e)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139b91d)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813aaa76)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/inline.c (ffffffff813b0be2)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
```
In fs/ext4/namei.c (ffffffff813d3b75)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813f8d88)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_xattr_get_block
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_get
```
```
In fs/jbd2/journal.c (ffffffff81404c02)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
```
</details>
</li>
</ul>

## Differences
