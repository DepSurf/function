# Function: <code>inode_set_atime_to_ts</code>

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
In fs/inode.c (ffffffff81509eb0)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/inode.c:inode_update_timestamps
```
```
In fs/attr.c (ffffffff8150cb1d)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/attr.c:setattr_copy
```
```
In fs/libfs.c (ffffffff8152343a)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
```
```
In fs/stack.c (ffffffff81535ab9)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_attr_all
```
```
In fs/kernfs/inode.c (ffffffff815b954e)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff815c1437)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
```
```
In fs/ext4/inode.c (ffffffff815eff51)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815f5cde)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/xattr.c (ffffffff8163ee67)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/squashfs/inode.c (ffffffff81660ca4)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fat/inode.c (ffffffff81674b0d)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81675e08)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In fs/ecryptfs/file.c (ffffffff81679d3b)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8167a7b5)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_get_link
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/fuse/inode.c (ffffffff8169e374)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In ipc/mqueue.c (ffffffff816be1ce)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_read_file
```
```
In drivers/tty/tty_io.c (ffffffff81ae4e6e)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_update_time
```
```
In drivers/usb/core/devio.c (ffffffff81d4eede)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
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
