# Function: <code>inode_set_mtime_to_ts</code>

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
In kernel/bpf/inode.c (ffffffff8133fb9e)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
```
In mm/shmem.c (ffffffff813ed07d)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
```
In fs/inode.c (ffffffff81509e84)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/inode.c:inode_update_timestamps
```
```
In fs/attr.c (ffffffff8150cb35)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/attr.c:setattr_copy
```
```
In fs/libfs.c (ffffffff815231d2)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_timestamp
  - fs/libfs.c:simple_rename_timestamp
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/stack.c (ffffffff81535ac9)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_attr_all
```
```
In fs/kernfs/inode.c (ffffffff815b955e)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff815c14ff)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
```
```
In fs/ext4/extents.c (ffffffff815d31ae)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/inline.c (ffffffff815e8842)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
```
```
In fs/ext4/inode.c (ffffffff815f4b9a)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff815f5cfe)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/namei.c (ffffffff81610c8b)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:add_dirent_to_buf
```
```
In fs/ext4/super.c (ffffffff8162dddf)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
```
```
In fs/squashfs/inode.c (ffffffff81660ca4)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/ramfs/inode.c (ffffffff81666853)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
```
In fs/hugetlbfs/inode.c (ffffffff816675c9)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
```
```
In fs/fat/inode.c (ffffffff81674b0d)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81675e58)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
```
```
In fs/ecryptfs/inode.c (ffffffff8167bcb3)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/fuse/dir.c (ffffffff81693d4a)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/inode.c (ffffffff8169b9ee)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
```
```
In fs/pstore/inode.c (ffffffff816acbf8)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In fs/efivarfs/file.c (ffffffff816ae55b)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In security/apparmor/apparmorfs.c (ffffffff81735ff1)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
```
```
In security/apparmor/policy_unpack.c (ffffffff8174979d)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
```
```
In drivers/tty/tty_io.c (ffffffff81ae4e1e)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_update_time
```
```
In drivers/usb/core/devio.c (ffffffff81d4f718)
Location: include/linux/fs.h:1570
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
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
