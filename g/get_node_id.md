# Function: <code>get_node_id</code>

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
In fs/fuse/dir.c (ffffffff813120c7)
Location: fs/fuse/fuse_i.h:683
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81317ae7)
Location: fs/fuse/fuse_i.h:683
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff8131b223)
Location: fs/fuse/fuse_i.h:683
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_statfs
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
In fs/fuse/dir.c (ffffffff8134749c)
Location: fs/fuse/fuse_i.h:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8134c403)
Location: fs/fuse/fuse_i.h:693
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff8134f8f1)
Location: fs/fuse/fuse_i.h:693
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
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
In fs/fuse/dir.c (ffffffff8135cdbd)
Location: fs/fuse/fuse_i.h:694
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81361d13)
Location: fs/fuse/fuse_i.h:694
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff81365211)
Location: fs/fuse/fuse_i.h:694
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:694
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
In fs/fuse/dir.c (ffffffff8137179c)
Location: fs/fuse/fuse_i.h:690
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff813766df)
Location: fs/fuse/fuse_i.h:690
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff813798d0)
Location: fs/fuse/fuse_i.h:690
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:690
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
In fs/fuse/dir.c (ffffffff813964bf)
Location: fs/fuse/fuse_i.h:689
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8139b47f)
Location: fs/fuse/fuse_i.h:689
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff8139e770)
Location: fs/fuse/fuse_i.h:689
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
```
```
In fs/fuse/xattr.c (0)
Location: fs/fuse/fuse_i.h:689
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
In fs/fuse/dir.c (ffffffff813c732f)
Location: fs/fuse/fuse_i.h:695
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff813c798b)
Location: fs/fuse/fuse_i.h:695
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff813cdb5e)
Location: fs/fuse/fuse_i.h:695
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff813d03d7)
Location: fs/fuse/fuse_i.h:695
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
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
In fs/fuse/dir.c (ffffffff813e0511)
Location: fs/fuse/fuse_i.h:763
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff813e0bdb)
Location: fs/fuse/fuse_i.h:763
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff813e6f4e)
Location: fs/fuse/fuse_i.h:763
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff813e9947)
Location: fs/fuse/fuse_i.h:763
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff813ea5eb)
Location: fs/fuse/fuse_i.h:763
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/dir.c (ffffffff8140c176)
Location: fs/fuse/fuse_i.h:779
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8140c7f4)
Location: fs/fuse/fuse_i.h:779
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff81412f8e)
Location: fs/fuse/fuse_i.h:779
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff81415aab)
Location: fs/fuse/fuse_i.h:779
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8141618a)
Location: fs/fuse/fuse_i.h:779
Inline: True
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
In fs/fuse/dir.c (ffffffff81425c8b)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81426382)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8142d0de)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff8142f8eb)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8143006e)
Location: fs/fuse/fuse_i.h:774
Inline: True
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
In fs/fuse/dir.c (ffffffff81475204)
Location: fs/fuse/fuse_i.h:775
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81475892)
Location: fs/fuse/fuse_i.h:775
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8147c3a9)
Location: fs/fuse/fuse_i.h:775
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff8147f759)
Location: fs/fuse/fuse_i.h:775
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8148000e)
Location: fs/fuse/fuse_i.h:775
Inline: True
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
In fs/fuse/dir.c (ffffffff8148fd1f)
Location: fs/fuse/fuse_i.h:849
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814905ac)
Location: fs/fuse/fuse_i.h:849
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff814973bc)
Location: fs/fuse/fuse_i.h:849
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff8149adeb)
Location: fs/fuse/fuse_i.h:849
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8149b6f1)
Location: fs/fuse/fuse_i.h:849
Inline: True
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
In fs/fuse/dir.c (ffffffff81495756)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81495fdc)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8149c510)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff814a003b)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff814a08f9)
Location: fs/fuse/fuse_i.h:858
Inline: True
```
```
In fs/fuse/ioctl.c (ffffffff814a21d2)
Location: fs/fuse/fuse_i.h:858
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
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
In fs/fuse/dir.c (ffffffff814ed1ef)
Location: fs/fuse/fuse_i.h:863
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814eda9c)
Location: fs/fuse/fuse_i.h:863
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff814f40d0)
Location: fs/fuse/fuse_i.h:863
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff814f804b)
Location: fs/fuse/fuse_i.h:863
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff814f87c9)
Location: fs/fuse/fuse_i.h:863
Inline: True
```
```
In fs/fuse/ioctl.c (ffffffff814fa272)
Location: fs/fuse/fuse_i.h:863
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
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
In fs/fuse/dir.c (ffffffff8157c069)
Location: fs/fuse/fuse_i.h:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8157ca25)
Location: fs/fuse/fuse_i.h:884
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff81583ad5)
Location: fs/fuse/fuse_i.h:884
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff815880ab)
Location: fs/fuse/fuse_i.h:884
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff815885aa)
Location: fs/fuse/fuse_i.h:884
Inline: True
```
```
In fs/fuse/ioctl.c (ffffffff8158a537)
Location: fs/fuse/fuse_i.h:884
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
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
In fs/fuse/dir.c (ffffffff81621a79)
Location: fs/fuse/fuse_i.h:887
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81622545)
Location: fs/fuse/fuse_i.h:887
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff81629ad5)
Location: fs/fuse/fuse_i.h:887
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff8162e42b)
Location: fs/fuse/fuse_i.h:887
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8162ea6a)
Location: fs/fuse/fuse_i.h:887
Inline: True
```
```
In fs/fuse/ioctl.c (ffffffff8162fe66)
Location: fs/fuse/fuse_i.h:887
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
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
In fs/fuse/dir.c (ffffffff81659f05)
Location: fs/fuse/fuse_i.h:892
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8165a9a3)
Location: fs/fuse/fuse_i.h:892
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff81661ce5)
Location: fs/fuse/fuse_i.h:892
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff8166666b)
Location: fs/fuse/fuse_i.h:892
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff81666cca)
Location: fs/fuse/fuse_i.h:892
Inline: True
```
```
In fs/fuse/ioctl.c (ffffffff81668066)
Location: fs/fuse/fuse_i.h:892
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
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
In fs/fuse/dir.c (ffffffff81693b97)
Location: fs/fuse/fuse_i.h:919
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81694673)
Location: fs/fuse/fuse_i.h:919
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8169bbf5)
Location: fs/fuse/fuse_i.h:919
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_sync_fs
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff816a094b)
Location: fs/fuse/fuse_i.h:919
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff816a0fda)
Location: fs/fuse/fuse_i.h:919
Inline: True
```
```
In fs/fuse/ioctl.c (ffffffff816a2366)
Location: fs/fuse/fuse_i.h:919
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
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
In fs/fuse/dir.c (ffff8000105094ac)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffff800010509f10)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffff800010510ee8)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffff800010514294)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffff800010514ae8)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
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
In fs/fuse/dir.c (c06c53d0)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (c06c5b5c)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_lk_fill
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (c06cc810)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (c06cf0f0)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (c06cf850)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
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
In fs/fuse/dir.c (c00000000064f24c)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (c00000000064fc60)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (c000000000658c90)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (c00000000065c538)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (c00000000065d0dc)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/readdir.c:parse_dirplusfile
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
In fs/fuse/dir.c (ffffffe000374fa0)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffe000375696)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffe00037b784)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffe00037dd7c)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
```
```
In fs/fuse/readdir.c (ffffffe00037e7bc)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/dir.c (ffffffff8141e26b)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8141e962)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff814256be)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff81427ecb)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8142864e)
Location: fs/fuse/fuse_i.h:774
Inline: True
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
In fs/fuse/dir.c (ffffffff8140eceb)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8140f3e2)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8141613e)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff8141894b)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff814190ce)
Location: fs/fuse/fuse_i.h:774
Inline: True
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
In fs/fuse/dir.c (ffffffff8141a40b)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8141ab02)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8142185e)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff8142406b)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff814247ee)
Location: fs/fuse/fuse_i.h:774
Inline: True
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
In fs/fuse/dir.c (ffffffff8143116b)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81431982)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff814386de)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_statfs
  - fs/fuse/inode.c:fuse_inode_eq
```
```
In fs/fuse/xattr.c (ffffffff8143aeab)
Location: fs/fuse/fuse_i.h:774
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8143b35e)
Location: fs/fuse/fuse_i.h:774
Inline: True
```
</details>
</li>
</ul>

## Differences
