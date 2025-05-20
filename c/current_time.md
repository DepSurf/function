# Function: <code>current_time</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timespec current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262e40)
Location: fs/inode.c:2116
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:__atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_get_inode
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81262e40-ffffffff81262eab: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timespec current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812706e0)
Location: fs/inode.c:2106
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:__atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/apparmorfs.c:__aafs_setup_d_inode
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff812706e0-ffffffff8127074a: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timespec current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293020)
Location: fs/inode.c:2119
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:__atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81293020-ffffffff81293085: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8c50)
Location: fs/inode.c:2141
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:__atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/dir.c:fat_remove_entries
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_cont_expand
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/inode.c:fat_write_end
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff812b8c50-ffffffff812b8cdb: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cdda0)
Location: fs/inode.c:2148
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo_xattr
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff812cdda0-ffffffff812cde1b: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eabd0)
Location: fs/inode.c:2180
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff812eabd0-ffffffff812eac4b: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc700)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff812fc700-ffffffff812fc779: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335730)
Location: fs/inode.c:2282
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/pipe.c:get_pipe_inode
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:mknod_ptmx
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81335730-ffffffff81335818: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813410b0)
Location: fs/inode.c:2283
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/pipe.c:get_pipe_inode
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:mknod_ptmx
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff813410b0-ffffffff81341198: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813474b0)
Location: fs/inode.c:2309
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff813474b0-ffffffff81347597: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394f10)
Location: fs/inode.c:2314
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81394f10-ffffffff81394ff7: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814172e0)
Location: fs/inode.c:2395
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_create
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff814172e0-ffffffff814173e2: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a2890)
Location: fs/inode.c:2444
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_fileattr_set
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_modified_flags
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff814a2890-ffffffff814a2995: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d79d0)
Location: fs/inode.c:2489
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
  - mm/shmem.c:shmem_fileattr_set
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_modified_flags
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_tmpfile
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff814d79d0-ffffffff814d7ad5: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509c51)
Location: fs/inode.c:2492
Inline: True
Inline callers:
  - fs/inode.c:inode_needs_update_time
  - fs/inode.c:inode_update_timestamps
  - fs/inode.c:inode_update_timestamps
Direct callers:
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/locks.c:lease_get_mtime
  - fs/configfs/inode.c:configfs_setattr
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff8150a030-ffffffff8150a111: current_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac188)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffff8000103ac188-ffff8000103ac208: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d420)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/nsfs.c:__ns_get_path
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c058d420-c058d4d4: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a76d0)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
c0000000004a76d0-c0000000004a7778: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000271708)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffe000271708-ffffffe00027178e: current_time (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4ce0)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff812f4ce0-ffffffff812f4d59: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5900)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff812e5900-ffffffff812e5979: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2af0)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff812f2af0-ffffffff812f2b69: current_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct timespec64 current_time(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304200)
Location: fs/inode.c:2222
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_dentry_finalize
  - kernel/bpf/inode.c:bpf_get_inode
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_truncate_range
  - fs/pipe.c:create_pipe_files
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/locks.c:lease_get_mtime
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/inode.c:configfs_new_inode
  - fs/configfs/inode.c:configfs_setattr
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/misc.c:fat_truncate_time
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_get_inode
  - security/inode.c:securityfs_create_dentry
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:__aafs_profile_migrate_dents
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - security/apparmor/policy_unpack.c:__aa_loaddata_update
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff81304200-ffffffff81304279: current_time (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct timespec</code> ➡️ <code>struct timespec64</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
