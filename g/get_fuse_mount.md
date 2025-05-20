# Function: <code>get_fuse_mount</code>

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
In fs/fuse/dir.c (ffffffff8148fba8)
Location: fs/fuse/fuse_i.h:834
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8149079f)
Location: fs/fuse/fuse_i.h:834
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/xattr.c (ffffffff8149abeb)
Location: fs/fuse/fuse_i.h:834
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8149bea3)
Location: fs/fuse/fuse_i.h:834
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/dax.c (ffffffff8149c322)
Location: fs/fuse/fuse_i.h:834
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (ffffffff814955d8)
Location: fs/fuse/fuse_i.h:843
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814961cf)
Location: fs/fuse/fuse_i.h:843
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/xattr.c (ffffffff8149fe3b)
Location: fs/fuse/fuse_i.h:843
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff814a0fb7)
Location: fs/fuse/fuse_i.h:843
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff814a21a5)
Location: fs/fuse/fuse_i.h:843
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
```
In fs/fuse/dax.c (ffffffff814a2352)
Location: fs/fuse/fuse_i.h:843
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (ffffffff814ed068)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff814edc8f)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/xattr.c (ffffffff814f7e4b)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff814f9067)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff814fa245)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
```
In fs/fuse/dax.c (ffffffff814fa3f2)
Location: fs/fuse/fuse_i.h:848
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (ffffffff8157be9d)
Location: fs/fuse/fuse_i.h:869
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8157d03f)
Location: fs/fuse/fuse_i.h:869
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/xattr.c (ffffffff81587e9b)
Location: fs/fuse/fuse_i.h:869
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff81588b06)
Location: fs/fuse/fuse_i.h:869
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff8158a504)
Location: fs/fuse/fuse_i.h:869
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_fileattr_set
  - fs/fuse/ioctl.c:fuse_fileattr_get
```
```
In fs/fuse/dax.c (0)
Location: fs/fuse/fuse_i.h:869
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (ffffffff816218ad)
Location: fs/fuse/fuse_i.h:872
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81622b7f)
Location: fs/fuse/fuse_i.h:872
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/xattr.c (ffffffff8162e1fb)
Location: fs/fuse/fuse_i.h:872
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff8162eff6)
Location: fs/fuse/fuse_i.h:872
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff8162fdf5)
Location: fs/fuse/fuse_i.h:872
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
```
```
In fs/fuse/dax.c (0)
Location: fs/fuse/fuse_i.h:872
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (ffffffff81659cfd)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff8165afbf)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/xattr.c (ffffffff8166643b)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff81667259)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff81667ff5)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
```
```
In fs/fuse/dax.c (0)
Location: fs/fuse/fuse_i.h:877
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
In fs/fuse/dir.c (ffffffff8169396c)
Location: fs/fuse/fuse_i.h:904
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_flush_times
  - fs/fuse/dir.c:fuse_readlink_page
  - fs/fuse/dir.c:fuse_access
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_symlink
  - fs/fuse/dir.c:fuse_mkdir
  - fs/fuse/dir.c:fuse_mknod
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/file.c (ffffffff81694c8f)
Location: fs/fuse/fuse_i.h:904
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_lseek
  - fs/fuse/file.c:fuse_bmap
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_flush_writepages
  - fs/fuse/file.c:fuse_do_readpage
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/xattr.c (ffffffff816a071b)
Location: fs/fuse/fuse_i.h:904
Inline: True
Inline callers:
  - fs/fuse/xattr.c:fuse_removexattr
  - fs/fuse/xattr.c:fuse_listxattr
  - fs/fuse/xattr.c:fuse_getxattr
  - fs/fuse/xattr.c:fuse_setxattr
```
```
In fs/fuse/readdir.c (ffffffff816a15a9)
Location: fs/fuse/fuse_i.h:904
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In fs/fuse/ioctl.c (ffffffff816a22f5)
Location: fs/fuse/fuse_i.h:904
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_priv_ioctl_prepare
```
```
In fs/fuse/dax.c (0)
Location: fs/fuse/fuse_i.h:904
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_send_removemapping
  - fs/fuse/dax.c:fuse_setup_one_mapping
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
