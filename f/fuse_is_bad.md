# Function: <code>fuse_is_bad</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148f64a)
Location: fs/fuse/fuse_i.h:870
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814918d4)
Location: fs/fuse/fuse_i.h:870
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_compat_ioctl
  - fs/fuse/file.c:fuse_file_ioctl
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8149794b)
Location: fs/fuse/fuse_i.h:870
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff8149ae85)
Location: fs/fuse/fuse_i.h:870
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_listxattr
```
```
In fs/fuse/acl.c (ffffffff8149b024)
Location: fs/fuse/fuse_i.h:870
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8149c1fc)
Location: fs/fuse/fuse_i.h:870
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/dir.c (ffffffff8149506a)
Location: fs/fuse/fuse_i.h:886
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8149ba5f)
Location: fs/fuse/fuse_i.h:886
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8149cb7b)
Location: fs/fuse/fuse_i.h:886
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff814a00d5)
Location: fs/fuse/fuse_i.h:886
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_listxattr
```
```
In fs/fuse/acl.c (ffffffff814a0274)
Location: fs/fuse/fuse_i.h:886
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814a14ac)
Location: fs/fuse/fuse_i.h:886
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/fuse/ioctl.c (ffffffff814a1ff4)
Location: fs/fuse/fuse_i.h:886
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
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
In fs/fuse/dir.c (ffffffff814ecafa)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814f345f)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_readpage
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff814f4678)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff814f80e5)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_listxattr
```
```
In fs/fuse/acl.c (ffffffff814f8294)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff814f955c)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/fuse/ioctl.c (ffffffff814fa094)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
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
In fs/fuse/dir.c (ffffffff8157b868)
Location: fs/fuse/fuse_i.h:912
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81582ee2)
Location: fs/fuse/fuse_i.h:912
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_read_folio
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8158424a)
Location: fs/fuse/fuse_i.h:912
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff81588135)
Location: fs/fuse/fuse_i.h:912
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_listxattr
```
```
In fs/fuse/acl.c (ffffffff81588334)
Location: fs/fuse/fuse_i.h:912
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8158975b)
Location: fs/fuse/fuse_i.h:912
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/fuse/ioctl.c (ffffffff8158a304)
Location: fs/fuse/fuse_i.h:912
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
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
In fs/fuse/dir.c (ffffffff81621228)
Location: fs/fuse/fuse_i.h:915
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81628e62)
Location: fs/fuse/fuse_i.h:915
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_read_folio
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8162a2ea)
Location: fs/fuse/fuse_i.h:915
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff8162e4c5)
Location: fs/fuse/fuse_i.h:915
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_listxattr
```
```
In fs/fuse/acl.c (ffffffff8162e7bb)
Location: fs/fuse/fuse_i.h:915
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff8162fd5b)
Location: fs/fuse/fuse_i.h:915
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/fuse/ioctl.c (ffffffff8162fe26)
Location: fs/fuse/fuse_i.h:915
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
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
In fs/fuse/dir.c (ffffffff81659678)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81661082)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_read_folio
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff816624fa)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff81666705)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_listxattr
```
```
In fs/fuse/acl.c (ffffffff816669fb)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff81667f5e)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/fuse/ioctl.c (ffffffff81668026)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
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
In fs/fuse/dir.c (ffffffff81693367)
Location: fs/fuse/fuse_i.h:947
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_rename2
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8169af42)
Location: fs/fuse/fuse_i.h:947
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_read_iter
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_read_folio
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/inode.c (ffffffff8169c8b5)
Location: fs/fuse/fuse_i.h:947
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_evict_inode
```
```
In fs/fuse/xattr.c (ffffffff816a09e5)
Location: fs/fuse/fuse_i.h:947
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_xattr_set
  - fs/fuse/xattr.c:fuse_xattr_get
  - fs/fuse/xattr.c:fuse_listxattr
```
```
In fs/fuse/acl.c (ffffffff816a0d0b)
Location: fs/fuse/fuse_i.h:947
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_inode_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In fs/fuse/readdir.c (ffffffff816a225e)
Location: fs/fuse/fuse_i.h:947
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In fs/fuse/ioctl.c (ffffffff816a2326)
Location: fs/fuse/fuse_i.h:947
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
  - fs/fuse/ioctl.c:fuse_file_compat_ioctl
  - fs/fuse/ioctl.c:fuse_file_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
