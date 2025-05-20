# Function: <code>inode_is_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123f07e)
Location: include/linux/fs.h:765
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
```
```
In fs/dcache.c (ffffffff8124aaad)
Location: include/linux/fs.h:765
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
```
```
In fs/attr.c (ffffffff81251c57)
Location: include/linux/fs.h:765
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/inode.c (ffffffff812ca702)
Location: include/linux/fs.h:765
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff812d7731)
Location: include/linux/fs.h:765
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/extents.c (ffffffff812fa99e)
Location: include/linux/fs.h:765
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/fuse/dir.c (ffffffff81348c2a)
Location: include/linux/fs.h:765
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
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
In fs/namei.c (ffffffff81251e4e)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
```
```
In fs/dcache.c (ffffffff8125da6d)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
```
```
In fs/attr.c (ffffffff81264e57)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/inode.c (ffffffff812e0396)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff812ed321)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/extents.c (ffffffff8131093e)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/fuse/dir.c (ffffffff8135e44a)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
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
In fs/namei.c (ffffffff8125dcb0)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
```
```
In fs/dcache.c (ffffffff8126b22d)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
```
```
In fs/attr.c (ffffffff8127267e)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff812eeecb)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813047c7)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff8131cf3d)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff8133bf81)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/fuse/dir.c (ffffffff81372f4a)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff8137fb6d)
Location: include/linux/fs.h:737
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff81280010)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
```
```
In fs/dcache.c (ffffffff8128dab6)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
```
```
In fs/attr.c (ffffffff81294f9e)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff813139cb)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813291d7)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff8134155d)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff81360491)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/fuse/dir.c (ffffffff81397c5a)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff813a4b7d)
Location: include/linux/fs.h:741
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff812a7c74)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/dcache.c (ffffffff812b4db6)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/dcache.c:dentry_update_name_case
```
```
In fs/attr.c (ffffffff812bb198)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff813418bb)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff81357536)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff8136f59d)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff8138e3d5)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffff813c6eda)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff813d3f1d)
Location: include/linux/fs.h:743
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff812bcd14)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff812d0388)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff81358f0b)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff8136f866)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff81387a2d)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff813a699e)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffff813e00ca)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff813ee5ad)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff812d9825)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff812ed3a3)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff81381e8b)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff81398dc6)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813b1a9d)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff813d1217)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffff8140bcbf)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff8141a85d)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff812eb335)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff812fee07)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff8139a43b)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813b1846)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813caaed)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff813ea8f4)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffff8142576f)
Location: include/linux/fs.h:820
Inline: True
```
```
In fs/pstore/inode.c (ffffffff814346cd)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff81323fa3)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff81337f07)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff813e586b)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813e90e3)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inode.c (ffffffff813fd4a6)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff81416adb)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff8143688a)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/fuse/dir.c (ffffffff81474e00)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff81484497)
Location: include/linux/fs.h:838
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff8132f5a3)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff81343871)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff813f708b)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813faf49)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inode.c (ffffffff8140fc26)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff8142a04b)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff8144f2aa)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/fuse/dir.c (ffffffff8148f910)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff814a1ae7)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff81334c63)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff81349bd5)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff813fd53b)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814013e5)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inode.c (ffffffff81415fe6)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff81430d4b)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff81454b6a)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/fuse/dir.c (ffffffff81495340)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff814a7c17)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff81382663)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff81397992)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff8144f83b)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81453965)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8145ef1e)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81469556)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/xattr.c (ffffffff814a8c90)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/orphan.c (ffffffff814b16bd)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fuse/dir.c (ffffffff814ecdd0)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffff814fff07)
Location: include/linux/fs.h:814
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff81401bc4)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff81419a12)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff814cc702)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814d14cb)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff814dd6a7)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814e9336)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/xattr.c (ffffffff8153023a)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/orphan.c (ffffffff8153a1c3)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fuse/dir.c (ffffffff8157bb90)
Location: include/linux/fs.h:769
Inline: True
```
```
In fs/pstore/inode.c (ffffffff815910a0)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff8148bd04)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff814a5a32)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff81564e22)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81569ff3)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815766da)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81582e37)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/xattr.c (ffffffff815cec3e)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/orphan.c (ffffffff815d8733)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fuse/dir.c (ffffffff81621570)
Location: include/linux/fs.h:784
Inline: True
```
```
In fs/pstore/inode.c (ffffffff81638680)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff814c0804)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff814daae1)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff8159caba)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815a1dea)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815ade6a)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815b99f7)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/xattr.c (ffffffff8160651d)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/orphan.c (ffffffff816102c7)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fuse/dir.c (ffffffff816599c0)
Location: include/linux/fs.h:799
Inline: True
```
```
In fs/pstore/inode.c (ffffffff81670a80)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff814f2ce4)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff8150d081)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff815d576a)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815da927)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815e6c2a)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815f2777)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/xattr.c (ffffffff8163f25d)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ext4/orphan.c (ffffffff81649087)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_del
  - fs/ext4/orphan.c:ext4_orphan_add
```
```
In fs/fuse/dir.c (ffffffff81693630)
Location: include/linux/fs.h:832
Inline: True
```
```
In fs/pstore/inode.c (ffffffff816ac96c)
Location: include/linux/fs.h:832
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffff800010394ac0)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffff8000103b030c)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffff80001046ce04)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffff800010486174)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffff8000104a26f8)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffff8000104c2e58)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffff800010508f5c)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffff80001051a444)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (c057aa60)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (c058fb84)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (c062e448)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (c0647fc8)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (c0664968)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (c06860c4)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/fuse/dir.c (c06c4efc)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (c06d4968)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (c00000000048d9dc)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (c0000000004abb20)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (c00000000058cac0)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (c0000000005abd3c)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (c0000000005cf56c)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (c0000000005fafb0)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (c00000000064eb3c)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (c000000000663dcc)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffe000263522)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffe0002746ca)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffe0002fa1d8)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffe00030e21a)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffe00032439e)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffe00033e5b0)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffe000374a56)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_set_nowrite
```
```
In fs/pstore/inode.c (ffffffe0003835b2)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff812e3915)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff812f73e7)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff81392a1b)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813a9e26)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813c30cd)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff813e2ed4)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffff8141dd4f)
Location: include/linux/fs.h:820
Inline: True
```
```
In fs/pstore/inode.c (ffffffff8142ccad)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff812d4555)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff812e8007)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff813834ab)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff8139a8b6)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813b3b5d)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff813d3954)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffff8140e7cf)
Location: include/linux/fs.h:820
Inline: True
```
```
In fs/pstore/inode.c (ffffffff8141d72d)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff812e1725)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff812f51f7)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff8139037b)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813a7686)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813c055d)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff813e0254)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffff81419eef)
Location: include/linux/fs.h:820
Inline: True
```
```
In fs/pstore/inode.c (ffffffff81428e4d)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
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
In fs/namei.c (ffffffff812f2675)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
```
In fs/attr.c (ffffffff81306387)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/ext4/extents.c (ffffffff813a420b)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inode.c (ffffffff813bbeb6)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_update_disksize_before_punch
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/namei.c (ffffffff813d568d)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_orphan_del
  - fs/ext4/namei.c:ext4_orphan_add
```
```
In fs/ext4/xattr.c (ffffffff813f5674)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/fuse/dir.c (ffffffff81430c5f)
Location: include/linux/fs.h:820
Inline: True
```
```
In fs/pstore/inode.c (ffffffff8143fd0d)
Location: include/linux/fs.h:820
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
</details>
</li>
</ul>

## Differences
