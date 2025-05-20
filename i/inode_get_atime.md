# Function: <code>inode_get_atime</code>

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
In fs/stat.c (ffffffff814e843b)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/inode.c (ffffffff8150c7db)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_update_timestamps
```
```
In fs/stack.c (ffffffff81535ab1)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_attr_all
```
```
In fs/ext4/inode.c (ffffffff815ec4dc)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f5cce)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/fat/inode.c (ffffffff81673ddf)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/fat/inode.c:__fat_write_inode
```
```
In fs/ecryptfs/file.c (ffffffff81679d33)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8167a7ad)
Location: include/linux/fs.h:1535
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
In fs/fuse/inode.c (ffffffff8169ea9b)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
```
```
In drivers/tty/tty_io.c (ffffffff81ae4e61)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_update_time
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
