# Function: <code>buffer_verified</code>

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
In fs/ext4/balloc.c (ffffffff8128efba)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81290e97)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff812935eb)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/namei.c (ffffffff812a1e53)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_find_entry
```
```
In fs/ext4/extents.c (ffffffff812c2c85)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/mballoc.c (ffffffff812cef5d)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/xattr.c (ffffffff812dcf5a)
Location: include/linux/jbd2.h:341
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
```
In fs/jbd2/journal.c (ffffffff812f0ea1)
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
In fs/ext4/balloc.c (ffffffff812bc4ea)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff812be40f)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff812c0bae)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/namei.c (ffffffff812d2ee2)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/extents.c (ffffffff812f2685)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/mballoc.c (ffffffff812fe909)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/xattr.c (ffffffff8130edb1)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/jbd2/journal.c (ffffffff8131e661)
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
In fs/ext4/balloc.c (ffffffff812d1b3a)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff812d3a64)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ialloc.c (ffffffff812d61de)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/namei.c (ffffffff812e8c32)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/extents.c (ffffffff81308655)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/mballoc.c (ffffffff8131496e)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/xattr.c (ffffffff81324c04)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_listxattr
```
```
In fs/jbd2/journal.c (ffffffff813346e1)
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
In fs/ext4/balloc.c (ffffffff812e31fa)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff812e5429)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff812e6de4)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff812f44cf)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8130bf87)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff81318587)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff8133ebe3)
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
In fs/jbd2/journal.c (ffffffff813494c1)
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
In fs/ext4/balloc.c (ffffffff81307bea)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81309e4c)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8130b7e4)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81318c0f)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81330ad7)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff8133ce34)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813631c3)
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
In fs/jbd2/journal.c (ffffffff8136db11)
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
In fs/ext4/balloc.c (ffffffff81335ada)
Location: include/linux/jbd2.h:336
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81337dda)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81339958)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81346b0c)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8135f077)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff8136b344)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813919f8)
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
In fs/jbd2/journal.c (ffffffff8139c2c1)
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
In fs/ext4/balloc.c (ffffffff8134cd5a)
Location: include/linux/jbd2.h:336
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8134f05a)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81350af8)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8135ecbc)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81377518)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff81383804)
Location: include/linux/jbd2.h:336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813aa61c)
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
In fs/jbd2/journal.c (ffffffff813b5081)
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
In fs/ext4/balloc.c (ffffffff81375781)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813780aa)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81379782)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81387f20)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813a08b8)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff813acfb1)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813d4824)
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
In fs/jbd2/journal.c (ffffffff813df6d1)
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
In fs/ext4/balloc.c (ffffffff8138d9f1)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8139044a)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81391ca2)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813a08f2)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813b971d)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff813c5ee8)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813edf04)
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
In fs/jbd2/journal.c (ffffffff813f9791)
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
In fs/ext4/balloc.c (ffffffff813d8ffc)
Location: include/linux/jbd2.h:332
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813db9ec)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813de521)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813eca11)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81405254)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff81412339)
Location: include/linux/jbd2.h:332
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff8143ae4c)
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
In fs/jbd2/journal.c (ffffffff8144706f)
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
In fs/ext4/balloc.c (ffffffff813eac0c)
Location: include/linux/jbd2.h:339
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813ed468)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813efdf1)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813fec32)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814184e3)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff814257d9)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff814539bc)
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
In fs/jbd2/journal.c (ffffffff814635cf)
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
In fs/ext4/balloc.c (ffffffff813f112c)
Location: include/linux/jbd2.h:339
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813f3acf)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff813f6080)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff814050e6)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8141ed28)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff8142c3e8)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff814592dc)
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
In fs/jbd2/journal.c (ffffffff8146872f)
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
In fs/ext4/balloc.c (ffffffff814430ec)
Location: include/linux/jbd2.h:339
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81445ba7)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81448911)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff814578f8)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8147242f)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff814802a9)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff814ad3f6)
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
In fs/jbd2/journal.c (ffffffff814be1df)
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
In fs/ext4/balloc.c (ffffffff814bef55)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff814c1bd6)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff814c56e1)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff814d5632)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814f34fb)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff815031f4)
Location: include/linux/jbd2.h:339
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff815354a0)
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
In fs/jbd2/journal.c (ffffffff81549922)
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
In fs/ext4/balloc.c (ffffffff81556e55)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81559e8e)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8155dc51)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff8156e0d5)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8158dade)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff8159dd33)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff815cf7de)
Location: include/linux/jbd2.h:338
Inline: True
Inline callers:
  - fs/ext4/xattr.c:__ext4_xattr_check_block
```
```
In fs/jbd2/journal.c (ffffffff815e8e6f)
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
In fs/ext4/balloc.c (ffffffff8158ee5e)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff81591cbf)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81595a71)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815a5f6e)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff815c4512)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff815d4597)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff816070dc)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/xattr.c:check_xattrs
```
```
In fs/jbd2/journal.c (ffffffff816206c0)
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
In fs/ext4/balloc.c (ffffffff815c7b6e)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/dir.c (ffffffff815caa2f)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff815ce721)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff815dedde)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff815fc7d1)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff8160cc47)
Location: include/linux/jbd2.h:329
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff8163fe1c)
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
In fs/ext4/balloc.c (ffff80001045f944)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (ffff800010462d38)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffff8000104654bc)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffff800010474228)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffff800010490188)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffff80001049d9b8)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffff8000104c6ed8)
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
In fs/jbd2/journal.c (ffff8000104d5e90)
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
In fs/ext4/balloc.c (c062019c)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (c0622fc4)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c0624b34)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c0635644)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (c06510a4)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (c065f520)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (c068aecc)
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
In fs/jbd2/journal.c (c069789c)
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
In fs/ext4/balloc.c (c00000000057bc00)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (c00000000057f6ec)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (c000000000581930)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (c000000000595708)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (c0000000005b742c)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (c0000000005c90a0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (c0000000005ff3fc)
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
In fs/jbd2/journal.c (c00000000061092c)
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
In fs/ext4/balloc.c (ffffffe0002ef0ea)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (ffffffe0002f16d2)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffe0002f2a9c)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffe0002ffc0a)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffe000315124)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffe000320670)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffe0003411a6)
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
In fs/jbd2/journal.c (ffffffe00034c2f6)
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
In fs/ext4/balloc.c (ffffffff81385fd1)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (ffffffff81388a2a)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8138a282)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81398ed2)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813b1cfd)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff813be4c8)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813e64e4)
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
In fs/jbd2/journal.c (ffffffff813f1d71)
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
In fs/ext4/balloc.c (ffffffff81376a61)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (ffffffff813794ba)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8137ad12)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81389962)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813a278d)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff813aef58)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813d6f64)
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
In fs/jbd2/journal.c (ffffffff813e27f1)
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
In fs/ext4/balloc.c (ffffffff81383aa1)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8138638a)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff81387be2)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff81396732)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813af55d)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff813bbac8)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813e3864)
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
In fs/jbd2/journal.c (ffffffff813ef0f1)
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
In fs/ext4/balloc.c (ffffffff813975cf)
Location: include/linux/jbd2.h:333
Inline: True
```
```
In fs/ext4/dir.c (ffffffff8139a071)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/extents.c (ffffffff8139b8c2)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/ialloc.c (ffffffff813aa9a1)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff813c3f73)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (ffffffff813d0a5a)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/xattr.c (ffffffff813f8c74)
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
In fs/jbd2/journal.c (ffffffff81404ac0)
Location: include/linux/jbd2.h:333
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
```
</details>
</li>
</ul>

## Differences
