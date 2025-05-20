# Function: <code>ecryptfs_dentry_to_lower</code>

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
In fs/ecryptfs/dentry.c (ffffffff81300c00)
Location: fs/ecryptfs/ecryptfs_kernel.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff8130138c)
Location: fs/ecryptfs/ecryptfs_kernel.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_removexattr
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_follow_link
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_getxattr
```
```
In fs/ecryptfs/super.c (ffffffff81303cf5)
Location: fs/ecryptfs/ecryptfs_kernel.h:512
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81306a20)
Location: fs/ecryptfs/ecryptfs_kernel.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
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
In fs/ecryptfs/dentry.c (ffffffff81334b50)
Location: fs/ecryptfs/ecryptfs_kernel.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff813354ac)
Location: fs/ecryptfs/ecryptfs_kernel.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_removexattr
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_get_link
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff81337cdc)
Location: fs/ecryptfs/ecryptfs_kernel.h:511
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8133ac08)
Location: fs/ecryptfs/ecryptfs_kernel.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
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
In fs/ecryptfs/dentry.c (ffffffff8134a920)
Location: fs/ecryptfs/ecryptfs_kernel.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff8134cd90)
Location: fs/ecryptfs/ecryptfs_kernel.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_get_link
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff8134daac)
Location: fs/ecryptfs/ecryptfs_kernel.h:511
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81350998)
Location: fs/ecryptfs/ecryptfs_kernel.h:511
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
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
In fs/ecryptfs/dentry.c (ffffffff8135f4b1)
Location: fs/ecryptfs/ecryptfs_kernel.h:510
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff81361910)
Location: fs/ecryptfs/ecryptfs_kernel.h:510
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff8136269c)
Location: fs/ecryptfs/ecryptfs_kernel.h:510
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813654a8)
Location: fs/ecryptfs/ecryptfs_kernel.h:510
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
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
In fs/ecryptfs/dentry.c (ffffffff81384171)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff813865e0)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff8138731c)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8138a178)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
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
In fs/ecryptfs/dentry.c (ffffffff813b2f15)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff813b52a5)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff813b6145)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813b8f58)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
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
In fs/ecryptfs/dentry.c (ffffffff813cc3f5)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff813ce7c5)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff813cf695)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813d24c8)
Location: fs/ecryptfs/ecryptfs_kernel.h:527
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
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
In fs/ecryptfs/dentry.c (ffffffff813f6f65)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff813f9315)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff813fa275)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813fcf68)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff81410e35)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff81413175)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff81414145)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81416e48)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff8145ed95)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff814600e3)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff81462385)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff814653aa)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff8147aa35)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff8147bd03)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff8147dcd5)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81480c4a)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff81480475)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff81481593)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff81483895)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8148653a)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff814d7d15)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff814d9353)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff814db045)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff814ddcca)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff81565355)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff81566b63)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_get_link
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff81568a05)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8156bdde)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff81608505)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff8160a133)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_set_acl
  - fs/ecryptfs/inode.c:ecryptfs_get_acl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_get_link
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff8160c385)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8160fefe)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff81640345)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff81641ff3)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_set_acl
  - fs/ecryptfs/inode.c:ecryptfs_get_acl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_get_link
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff81644275)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81647d8e)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff816798f5)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff8167b613)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_set_acl
  - fs/ecryptfs/inode.c:ecryptfs_get_acl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_get_link
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff8167d805)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81681241)
Location: fs/ecryptfs/ecryptfs_kernel.h:504
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffff8000104f1fd0)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffff8000104f4660)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffff8000104f55ec)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8868)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (c06af988)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (c06b2038)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (c06b2e4c)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (c06b6140)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (c000000000631a4c)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (c000000000634dec)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (c000000000636138)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (c00000000063a504)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffe0003618f8)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffe00036393e)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffe0003645e2)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffe00036717c)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff81409415)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff8140b755)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff8140c725)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f428)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff813f9e95)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff813fc1d5)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff813fd1a5)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813ffea8)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff81406795)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff81408ad5)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff81409aa5)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8140c7a8)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
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
In fs/ecryptfs/dentry.c (ffffffff8141c455)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/dentry.c:ecryptfs_d_revalidate
```
```
In fs/ecryptfs/inode.c (ffffffff8141e795)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/super.c (ffffffff8141f765)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81422428)
Location: fs/ecryptfs/ecryptfs_kernel.h:513
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
</details>
</li>
</ul>

## Differences
