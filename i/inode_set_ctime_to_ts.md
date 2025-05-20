# Function: <code>inode_set_ctime_to_ts</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: include/linux/fs.h:1600
Inline: True
```
```
In fs/inode.c (ffffffff81509e55)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/inode.c:inode_update_timestamps
```
```
In fs/attr.c (ffffffff8150cb4d)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/attr.c:setattr_copy
```
```
In fs/libfs.c (0)
Location: include/linux/fs.h:1600
Inline: True
```
```
In fs/stack.c (ffffffff81535adc)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_attr_all
```
```
In fs/kernfs/inode.c (ffffffff815b956e)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff815c1457)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
```
```
In fs/ext4/inode.c (ffffffff815eff21)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/xattr.c (ffffffff8163ee30)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/squashfs/inode.c (ffffffff81660ca4)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fat/inode.c (ffffffff81674b02)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/fat/misc.c (ffffffff81675e58)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In fs/ecryptfs/inode.c (ffffffff8167bcc6)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/fuse/dir.c (ffffffff81693f8e)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/inode.c (ffffffff8169b9ff)
Location: include/linux/fs.h:1600
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/pstore/inode.c (ffffffff816acbe9)
Location: include/linux/fs.h:1600
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
