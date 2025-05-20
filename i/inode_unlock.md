# Function: <code>inode_unlock</code>

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
In kernel/sched/debug.c (ffffffff810c9292)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff811324fb)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81132b52)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff81145534)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff81189ec5)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811a2a91)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff811c2cc7)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff811f4790)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
```
In fs/open.c (ffffffff8122fb00)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812318b5)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812398e6)
Location: include/linux/fs.h:740
Inline: True
```
```
In fs/namei.c (ffffffff812417bc)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:unlock_rename
  - fs/namei.c:unlock_rename
  - fs/namei.c:kern_path_locked
```
```
In fs/ioctl.c (ffffffff8124760a)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff81247f90)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff8124f844)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81254b3e)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8125aee6)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8125cb5e)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81269059)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff8127065b)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81275158)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81287131)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/dax.c:dax_do_io
```
```
In fs/locks.c (ffffffff8128e1f8)
Location: include/linux/fs.h:740
Inline: True
```
```
In fs/quota/dquot.c (ffffffff8129ed27)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff812b0d0f)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812b0fbf)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff812b433e)
Location: include/linux/fs.h:740
Inline: True
```
```
In fs/devpts/inode.c (ffffffff812bb521)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
```
```
In fs/ext4/file.c (ffffffff812bfd8f)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff812ca44b)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff812cfe12)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812edd4c)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (ffffffff812f9c81)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/hugetlbfs/inode.c (ffffffff81328581)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8132e468)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff813354e9)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_removexattr
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff813386cf)
Location: include/linux/fs.h:740
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff8134119c)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff81348700)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8134d524)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff81352113)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
```
```
In fs/tracefs/inode.c (ffffffff81354c1b)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8135552e)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_mkfile
```
```
In fs/efivarfs/file.c (ffffffff81356959)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81356e0f)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81362253)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
```
In security/inode.c (ffffffff813755c5)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff81381c48)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff813ad9c7)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/integrity/ima/ima_main.c (ffffffff813d3591)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c19f8)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81563645)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/base/devtmpfs.c (ffffffff815a4ae0)
Location: include/linux/fs.h:740
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
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
In kernel/sched/debug.c (ffffffff810cf2b2)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff8113c25b)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8113c8a2)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8114ee90)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811992b5)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811b28d1)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff811d2d27)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812052ba)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
```
In fs/open.c (ffffffff812420a0)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff81243e65)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8124c626)
Location: include/linux/fs.h:693
Inline: True
```
```
In fs/namei.c (ffffffff81254634)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:unlock_rename
  - fs/namei.c:unlock_rename
  - fs/namei.c:kern_path_locked
```
```
In fs/ioctl.c (ffffffff8125a5ea)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8125afd0)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff81262874)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812680a0)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8126e486)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812700ae)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff8127c039)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff81283e2b)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81288a85)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8129e8a3)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/locks.c (ffffffff812a21b4)
Location: include/linux/fs.h:693
Inline: True
```
```
In fs/quota/dquot.c (ffffffff812b467a)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff812c6663)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812c6853)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff812c9bce)
Location: include/linux/fs.h:693
Inline: True
```
```
In fs/devpts/inode.c (ffffffff812d0ca3)
Location: include/linux/fs.h:693
Inline: True
```
```
In fs/ext4/file.c (ffffffff812d4f9f)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff812e0128)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff812e5c02)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81303ccf)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (ffffffff8130fc51)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e2d1)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81344198)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff8134b2c4)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e46b)
Location: include/linux/fs.h:693
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff81356fd5)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8135e0a0)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81362e34)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff813683c3)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
```
```
In fs/tracefs/inode.c (ffffffff8136aedb)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8136b7ee)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_mkfile
```
```
In fs/efivarfs/file.c (ffffffff8136cda9)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8136d2d9)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81378a53)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
```
```
In security/inode.c (ffffffff8138bef5)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff813986c8)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff813c47d7)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/integrity/ima/ima_main.c (ffffffff813eaf34)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e39e8)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8158fda5)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/tpm_eventlog.c (ffffffff815a6cf9)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_open
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff815d3290)
Location: include/linux/fs.h:693
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
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
In kernel/sched/debug.c (ffffffff810d0421)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff8113d8ea)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8113df49)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff81151555)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811a1305)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811b9549)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff811db717)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81210b50)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
```
In fs/open.c (ffffffff8124d598)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8124f684)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8125873a)
Location: include/linux/fs.h:712
Inline: True
```
```
In fs/namei.c (ffffffff81260191)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff81265f62)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff81266fba)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812679ce)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff8127010a)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81275550)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8127bc86)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8127d7ae)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81289349)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff812914fb)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81295cfe)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff812ad3a7)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/locks.c (ffffffff812b0ef5)
Location: include/linux/fs.h:712
Inline: True
```
```
In fs/quota/dquot.c (ffffffff812c2408)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff812d3861)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812d3a51)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff812d7079)
Location: include/linux/fs.h:712
Inline: True
```
```
In fs/configfs/inode.c (ffffffff812de34d)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff812dec61)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff812dfd4a)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff812e2271)
Location: include/linux/fs.h:712
Inline: True
```
```
In fs/ext4/extents.c (ffffffff812ee215)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff812f18bc)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff81301d47)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff81309620)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8132b0fe)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff8133be10)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/hugetlbfs/inode.c (ffffffff81352f2b)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81358c7e)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff8135fe64)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff81362feb)
Location: include/linux/fs.h:712
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff8136bb77)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff81372b80)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8137784c)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff8137c9b3)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:debugfs_lookup
```
```
In fs/tracefs/inode.c (ffffffff8137f53f)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8137ff1b)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff813812dd)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8138183c)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8138d3d9)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff813a1973)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff813aeb25)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff813d8be0)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_create
  - security/apparmor/apparmorfs.c:aafs_create
```
```
In security/integrity/ima/ima_main.c (ffffffff813f7281)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814ef7d7)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff815a3e85)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/tpm1_eventlog.c (ffffffff815bbab9)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff815e7e63)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
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
In kernel/sched/debug.c (ffffffff810d7dd1)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff8114a6c0)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8114ad19)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8115dd55)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811b4e85)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811cf9c9)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff811f1517)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8122805a)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
```
```
In fs/open.c (ffffffff8126f518)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812715c4)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8127a501)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff81282871)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff81288842)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8128984a)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8128a24f)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff81292a4a)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81297e10)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8129e726)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812a024e)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff812abe69)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff812b424b)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812b8e65)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff812d16cd)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/locks.c (ffffffff812d49aa)
Location: include/linux/fs.h:716
Inline: True
```
```
In fs/quota/dquot.c (ffffffff812e62b1)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff812f8091)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812f8281)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff812fb822)
Location: include/linux/fs.h:716
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81302c8d)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff813035d1)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813046ca)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff81306c51)
Location: include/linux/fs.h:716
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81312cd5)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff813161a6)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff81328eb5)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff8132daea)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8134f56e)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813602af)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff81377a96)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8137d98e)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff81384b2a)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff81387c8b)
Location: include/linux/fs.h:716
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff813906fd)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff81397840)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8139c5ec)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff813a1887)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:debugfs_lookup
```
```
In fs/tracefs/inode.c (ffffffff813a458f)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff813a4f2b)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff813a62ed)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813a684c)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff813b279d)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff813c7773)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff813d4bd5)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff813ff1b7)
Location: include/linux/fs.h:716
Inline: True
```
```
In security/integrity/ima/ima_main.c (ffffffff8141f396)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81524353)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8160a785)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/tpm1_eventlog.c (ffffffff81622009)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff8164f203)
Location: include/linux/fs.h:716
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
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
In kernel/sched/debug.c (ffffffff810ddd51)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff81159130)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81159775)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8116ccb1)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811d3cea)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811f0b06)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff81213066)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8124d62d)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff8129416b)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff81294f68)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812972cc)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812a102a)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812ab647)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff812aecf6)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812afc00)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812b0630)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff812b884b)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812be45a)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff812c51e7)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812c69f0)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff812d2b2a)
Location: include/linux/fs.h:718
Inline: True
```
```
In fs/block_dev.c (ffffffff812db87a)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812e1a9b)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff812fc1b1)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/locks.c (ffffffff812ff000)
Location: include/linux/fs.h:718
Inline: True
```
```
In fs/quota/dquot.c (ffffffff8131410c)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff813253c1)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813255b1)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81328e7b)
Location: include/linux/fs.h:718
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81330bdc)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff81331548)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8133219a)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff81334c55)
Location: include/linux/fs.h:718
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81340b9c)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff81344003)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff8135720a)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff8135be8d)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8137d9d8)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff8138e2a9)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6701)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813ac3d0)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff813b3942)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff813b68f4)
Location: include/linux/fs.h:718
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff813bf6f4)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff813c6aa0)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff813cba14)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff813d0d0f)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
```
```
In fs/tracefs/inode.c (ffffffff813d3931)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff813d42c9)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff813d55fe)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813d5b6a)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff813e0cd5)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff813f6db6)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff81404dad)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff82717420)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
```
In security/integrity/ima/ima_main.c (ffffffff814513c6)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814565cd)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81457ae3)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a0a3)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816440df)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8165b9e7)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff8168ab92)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff8186f3a2)
Location: include/linux/fs.h:718
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffff810e8496)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff811660d0)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811666e5)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8117a9d1)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811e41ea)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff812012c6)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff81224b16)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81261a48)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812a8e2b)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812a9c58)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812abf7c)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812b602a)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812be257)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:path_openat
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff812c3de7)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812c4db0)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812c578e)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff812cd99b)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812d376a)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff812da3e7)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812dbbf0)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff812e7f0a)
Location: include/linux/fs.h:766
Inline: True
```
```
In fs/block_dev.c (ffffffff812f26b7)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812f6724)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81311a21)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/locks.c (ffffffff81314a27)
Location: include/linux/fs.h:766
Inline: True
```
```
In fs/quota/dquot.c (ffffffff8132b09c)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff8133c561)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff8133c751)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff8133fcbb)
Location: include/linux/fs.h:766
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81347fcc)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff81348938)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8134958a)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff8134bfa0)
Location: include/linux/fs.h:766
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813581ac)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff8135c143)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff8136f528)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff8137420a)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813961d8)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813a689a)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf4e1)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813c5690)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff813cce22)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfe44)
Location: include/linux/fs.h:766
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff813d8da5)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff813ddb3d)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff813e5260)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff813eb488)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
```
```
In fs/tracefs/inode.c (ffffffff813edfc1)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff813ee819)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff813efc4e)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813f016b)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff813fb4c5)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff81412866)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8141f78d)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828ceee5)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
```
In security/integrity/ima/ima_main.c (ffffffff8146e3d0)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81473a4d)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8147501b)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815719b3)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816623af)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8167aa37)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816aadc2)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff8188f86a)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffff810f08ca)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff81172c03)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81173297)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff81187823)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811fb3ba)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81218ebe)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff81235592)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8127cb7c)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812c5947)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812c6401)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812c877c)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812d2daa)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812daf24)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff812e0802)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812e1803)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812e2210)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff812ea74b)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812f15f1)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff812f89c9)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812fa26a)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff8130681a)
Location: include/linux/fs.h:781
Inline: True
```
```
In fs/block_dev.c (ffffffff81314068)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff813174a4)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81338f84)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/locks.c (ffffffff8133c396)
Location: include/linux/fs.h:781
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81352cac)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff813647cd)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813649ad)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81367fcb)
Location: include/linux/fs.h:781
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81370463)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff81370e8a)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813721d0)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff8137496c)
Location: include/linux/fs.h:781
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813817c4)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813852fd)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff81398b5e)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff8139d8f3)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813c0185)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813d108f)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9d22)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813f01bf)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff813f7994)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff813faa36)
Location: include/linux/fs.h:781
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813fcdd4)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81403714)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff814097eb)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81410d2f)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff814173d4)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8141a27e)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8141aabb)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff8141bf54)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8141c4e0)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8142783b)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8144053e)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8144d3d5)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828e8968)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8149bca0)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a174d)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a2c26)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a1ea4)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81697f6f)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff816b1407)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816e49be)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff818d98ca)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffff810fb0ca)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff8117eabf)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8117f107)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8119374e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff8120848a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8122676e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff812437d2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8128c2a6)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812d7357)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812d7e11)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812da18c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812e48ba)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812eca34)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff812f22ae)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812f32d3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812f3ce0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff812fc17b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff813031a1)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8130a5f9)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8130c06a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81319883)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/block_dev.c (ffffffff81327832)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff8132a322)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8134ed9a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff8134fb9d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff813548d6)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (ffffffff8136b031)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff8137ca5d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff8137cc3d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81380230)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81388953)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff8138936a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8138a7e0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff8138bd63)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff8138cbec)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81399d74)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8139de9b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813b15ec)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff813b636d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813d9455)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813ea75f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff81403dc2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8140a09f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81411864)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff81414906)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81416cb4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8141d673)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8142314b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8142a935)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff81431294)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff814340ee)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8143492b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff81435da4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81436330)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8144156b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff81459e0e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814671ed)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828f1454)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff814b5d79)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814bc1e0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814bd8f6)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c2d24)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816baacf)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff816d40e7)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81708cbe)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff8190b8aa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffff81105c2a)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff81192048)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81192619)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff811a8a0d)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff81230ffa)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81251701)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff812708b2)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812bf28d)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff8130c2c7)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8130de9f)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff813107ac)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8131c16f)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81327eeb)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff8132a4c5)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8132ba13)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8132c49b)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff81334cbb)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff8133fb75)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff81343579)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8134554a)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff8135382d)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff81360b18)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81364048)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813951f7)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81396408)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff8139b503)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
```
In fs/quota/dquot.c (ffffffff813b1908)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff813c63e9)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813c65c9)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813ca440)
Location: include/linux/fs.h:813
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813d3693)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff813d40da)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813d5bb8)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff813d7091)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813d7e9c)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/devpts/inode.c:mknod_ptmx
```
```
In fs/ext4/extents.c (ffffffff813e342b)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813e91a6)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff813fd277)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81401f34)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff814258c6)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_orphan_cleanup
```
```
In fs/ext4/xattr.c (ffffffff81436214)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff81451c12)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81457d8f)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81460129)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff814624cf)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
```
```
In fs/ecryptfs/crypto.c (ffffffff81465215)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8146c20c)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff814725bb)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8147a9f3)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff814810b4)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff81483ac3)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81484718)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff814857e8)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814860e1)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81492413)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814ad08e)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814bbabd)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff814f0528)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff815156a2)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8151c663)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8151e1e7)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d214)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8176ee6f)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81788474)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff817c3ece)
Location: include/linux/fs.h:813
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff819dda9a)
Location: include/linux/fs.h:813
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
In kernel/sched/debug.c (ffffffff8110427a)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff8118f1d8)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8118f789)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff811a5f8d)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff81215c31)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_iter_link_pin_kernel
  - kernel/bpf/inode.c:bpf_iter_link_pin_kernel
```
```
In kernel/events/core.c (ffffffff8123ac0a)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8125ce78)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8127b960)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812cae88)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff813181f5)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8131b5ff)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8131c9dc)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8132765f)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81334a16)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff81335a3c)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff81336fd3)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff81337a75)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff8134062b)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff8134bbdf)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8134f709)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8135189a)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff81360159)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/block_dev.c (ffffffff8136cafc)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81370e07)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813a66c7)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff813a8128)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff813acf42)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
```
In fs/quota/dquot.c (ffffffff813c2f08)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff813d8399)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813d8589)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813dc100)
Location: include/linux/fs.h:776
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813e53d3)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff813e5e1a)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813e7885)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff813e8d31)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813e9b3c)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/devpts/inode.c:mknod_ptmx
```
```
In fs/ext4/extents.c (ffffffff813f4c3c)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813fb5a6)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff8140fa7d)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff814147f4)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8143d246)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_orphan_cleanup
```
```
In fs/ext4/xattr.c (ffffffff8144ec54)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e1e6)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff814740df)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8147bd49)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff8147de1f)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
```
```
In fs/ecryptfs/crypto.c (ffffffff81480abb)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8148690f)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8148cd99)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8149567f)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff8149df6e)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff8149ecde)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a1118)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff814a1d68)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff814a2df8)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814a36e4)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff814afc63)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814ca5de)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814d943c)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff81bf15f6)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff81532574)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff815394d3)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8153afb7)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d934)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8178974f)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8179f394)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81c0e8f5)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff819dd48a)
Location: include/linux/fs.h:776
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
In kernel/sched/debug.c (ffffffff8110639f)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff81190005)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811906c9)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff811a68eb)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff81218967)
Location: include/linux/fs.h:777
Inline: True
```
```
In kernel/events/core.c (ffffffff8123f3da)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81261af8)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff81280ac7)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812d1966)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff8131e3e2)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8132173e)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff81322b4c)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8132f936)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff8133aba3)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:filename_create
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff8133bbac)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8133d306)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff8133e1d5)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff81346b5b)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff8135247a)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff81356211)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff813585ba)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff81366bef)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/block_dev.c (ffffffff8137339c)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81377865)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813ad75e)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff813af17c)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff813b42b6)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
```
In fs/quota/dquot.c (ffffffff813ca16d)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff813df239)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813df419)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813e30a0)
Location: include/linux/fs.h:777
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813ebfe3)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff813eca1a)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813ee255)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff813ef8a1)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813f07cc)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff813faf7c)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81401a76)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff81415e34)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff8141b362)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81443086)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_orphan_cleanup
```
```
In fs/ext4/xattr.c (ffffffff81455aff)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff81473759)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81479a4d)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff814815d9)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff81484209)
Location: include/linux/fs.h:777
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff814863a6)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8148c359)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff814925f8)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8149a6df)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff814a3f3e)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff814a4cbe)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a7248)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff814a7e98)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff814a902f)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814a96c4)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff814b5aa9)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814d0c0e)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814dfb2c)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff831fe37e)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8153a9b7)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81541bd3)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8154368e)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81670624)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8176d02f)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81782032)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff817bcfe8)
Location: include/linux/fs.h:777
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff819c36da)
Location: include/linux/fs.h:777
Inline: True
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
In kernel/sched/debug.c (ffffffff81123f16)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff811b8ee5)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811b95a9)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff811d00db)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff8124ef9d)
Location: include/linux/fs.h:789
Inline: True
```
```
In kernel/events/core.c (ffffffff81279f4a)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8129a408)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff812beee7)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff813170b8)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff8136b7b8)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8136ec1e)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8137003c)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8137d0e6)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff8138873d)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff8138982a)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8138ad00)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/readdir.c (ffffffff8138bb65)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff813945bb)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff813a083d)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff813a4741)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff813a6bfa)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff813b573f)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff813c3df5)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813fd0de)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff813fed2c)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff81403fb6)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
```
In fs/quota/dquot.c (ffffffff8141a921)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff81430be9)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81430dc9)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81434bb0)
Location: include/linux/fs.h:789
Inline: True
```
```
In fs/configfs/inode.c (ffffffff8143dd92)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff8143e94a)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8143fa39)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81441791)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff814426bc)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff8144d364)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81454006)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff81469315)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff8146e66b)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81496d34)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff814a9b1f)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff814b194c)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca380)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff814d1080)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff814d9399)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff814db889)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff814ddb36)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff814e3b69)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff814ea178)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff814f2131)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff814fbf48)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff814fcdb7)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff2ea)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81500198)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff815014e9)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81501a54)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8150e199)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8152993e)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff81538aaa)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff832e5690)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff81599369)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff815a1993)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff815a3dc1)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff815c59bc)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e48f4)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff817f27ff)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff818088d5)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81847368)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81a72f6a)
Location: include/linux/fs.h:789
Inline: True
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
In kernel/sched/build_utility.c (ffffffff8113d43f)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff811ebf16)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811ec67e)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff81204668)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff81296023)
Location: include/linux/fs.h:744
Inline: True
```
```
In kernel/events/core.c (ffffffff812cd33f)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff812f7428)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8131ab83)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff813827f7)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff813e9922)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff813ed4a5)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff813eea77)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff813f9e37)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8140973a)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff8140a50e)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8140bf77)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/readdir.c (ffffffff8140d0d7)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff81416c5f)
Location: include/linux/fs.h:744
Inline: True
```
```
In fs/namespace.c (ffffffff814255e2)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff81428760)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8142b899)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff8143aa21)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff8144ac5d)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81470866)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff814728c3)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff81479b67)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
```
In fs/quota/dquot.c (ffffffff81490b01)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff814aa931)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff814aab21)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff814aed0a)
Location: include/linux/fs.h:744
Inline: True
```
```
In fs/configfs/inode.c (ffffffff814b9684)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff814ba289)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff814bbf9f)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff814bd39b)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff814be44c)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff814c9e01)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814d158e)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff814e90fa)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff814eefe1)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81521cba)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff81531e17)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff8153a499)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff81556124)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8155dc33)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81566ba9)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff81569457)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff8156bbf4)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81571f43)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff81578aac)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81581ab2)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff8158c4a8)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff8158d5ec)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff815905b5)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81591358)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff81592836)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81592e6d)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff815a0fd5)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff815bf159)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff815d0058)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff8349c402)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8163dfda)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81647d4f)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8164a7d6)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff8167020c)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f253)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff819332af)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8194882c)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff8198be53)
Location: include/linux/fs.h:744
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81be58ca)
Location: include/linux/fs.h:744
Inline: True
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
In kernel/sched/build_utility.c (ffffffff81167e8f)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff81232376)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81232b5e)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8124c548)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff812f0eb4)
Location: include/linux/fs.h:759
Inline: True
```
```
In kernel/events/core.c (ffffffff813353df)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81360cd8)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8138e93b)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff813fc790)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff81471942)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff81475b2e)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff81477347)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8148372b)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81493dea)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:open_last_lookups
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff81494d97)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff81496997)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/readdir.c (ffffffff81497b77)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff814a217f)
Location: include/linux/fs.h:759
Inline: True
```
```
In fs/namespace.c (ffffffff814b1d62)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff814b5c90)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff814b8969)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff814c8ed8)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff814d938d)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81502306)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff815045b3)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff8150c507)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
```
In fs/posix_acl.c (ffffffff81515fb4)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff815246b1)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff815405a1)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff815407c1)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff815453aa)
Location: include/linux/fs.h:759
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81550e14)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff81551ac9)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff81553aca)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff8155500b)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff8155622c)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff8156247d)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8156a362)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff81582beb)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81589176)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff815be7be)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff815ce8aa)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff815d8a19)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff815f781c)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff815ffcb3)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8160a179)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff8160cff7)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff8160fc26)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81617387)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8161e06c)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81627932)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff81632d1d)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff81634448)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637a35)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81638958)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff8163a0c6)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8163a8ab)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8164a9ce)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8166b549)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8167dd48)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff83ed35de)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff816f5c04)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8170058f)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81703926)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff8172b7ac)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193df93)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81a91fff)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81aabcbc)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81afb8bd)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81d91b4a)
Location: include/linux/fs.h:759
Inline: True
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
In kernel/sched/build_utility.c (ffffffff81178552)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff81249006)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff812497de)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8126386f)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff8131db60)
Location: include/linux/fs.h:774
Inline: True
```
```
In kernel/events/core.c (ffffffff81366132)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81393098)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff813c1d0e)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8142fb9d)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff814a62a3)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff814aa490)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff814abcb4)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff814bb5ee)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814c8e58)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lock_rename_child
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff814ca124)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff814cb9d7)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/inode.c (ffffffff814d7244)
Location: include/linux/fs.h:774
Inline: True
```
```
In fs/namespace.c (ffffffff814e6db4)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
```
```
In fs/xattr.c (ffffffff814ea4de)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff814edb79)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff814ff112)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff815120b9)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff815399a9)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff8153bd5c)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff81543c7c)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
```
```
In fs/posix_acl.c (ffffffff8154d928)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff8155cad7)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff81578961)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81578b81)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff8157cf8a)
Location: include/linux/fs.h:774
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81588af4)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff815897f9)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8158b85a)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff8158cdab)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff8158dfdc)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff8159a1f4)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815a22c5)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff815b9769)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff815bf99c)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff815f54ce)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff8160617a)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff816105b9)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f7fc)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81637cac)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81642039)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff81644eaa)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff81647ab6)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8164f460)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8165619c)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8165fd08)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff8166afd0)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff8166c758)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166fe35)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81670d58)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff81672526)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81672e85)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81682d0e)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff816a3ca9)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff816b5f39)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff836f8658)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8172fe9a)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8173a625)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8173d956)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff8176762c)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982376)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81add87e)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81af751c)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81b49ca5)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81dffe28)
Location: include/linux/fs.h:774
Inline: True
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
In kernel/sched/build_utility.c (ffffffff81186272)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff81262e96)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff812636ce)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8127d5ff)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff8133ff70)
Location: include/linux/fs.h:807
Inline: True
```
```
In kernel/events/core.c (ffffffff8138f252)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff813bcd48)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff813eca8e)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
  - mm/shmem.c:shmem_file_write_iter
```
```
In mm/swapfile.c (ffffffff81469680)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff814d71f3)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff814db930)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff814dd154)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff814edb5e)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814fb717)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:filename_create
  - fs/namei.c:open_last_lookups
  - fs/namei.c:lock_rename_child
  - fs/namei.c:__kern_path_locked
```
```
In fs/fcntl.c (ffffffff814fc9f2)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff814fe287)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/inode.c (ffffffff815095c4)
Location: include/linux/fs.h:807
Inline: True
```
```
In fs/namespace.c (ffffffff8151abf4)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
```
```
In fs/xattr.c (ffffffff8151e37e)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff815218d9)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff81533d42)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff8154659a)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8156eba9)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff8157103c)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff8157917b)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/posix_acl.c (ffffffff81583758)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff81593294)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff815b10d2)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff815b1342)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff815b58d9)
Location: include/linux/fs.h:807
Inline: True
```
```
In fs/configfs/inode.c (ffffffff815c16c7)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff815c240c)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff815c4590)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff815c5af1)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff815c6d29)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff815d3044)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815dafee)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff815f24db)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff815f8742)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8162de15)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff8163eead)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff81649379)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff81668cd8)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8167119c)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8167b65c)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e3ba)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff81680f69)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81688a16)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8168fa1c)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81699b68)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff816a5310)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff816a68f5)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff816aaa52)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff816acc98)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff816ae566)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff816af227)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff816bf10e)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff816e0709)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff816f30d4)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff8392ba22)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff81770828)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8177b165)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8177e7b5)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff817a941c)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c983e)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81b30cae)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81b4ab0c)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81ba2095)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81ebc2c8)
Location: include/linux/fs.h:807
Inline: True
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
In kernel/sched/debug.c (ffff800010160d5c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffff8000101f39e8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffff8000101f40ac)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffff80001020c350)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffff800010291d2c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffff8000102b3ab0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffff8000102d5a74)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffff800010327980)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffff80001037c548)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037d1d0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffff80001037f60c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffff80001038c16c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffff8000103960ec)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffff80001039c384)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffff80001039e014)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffff80001039f2c8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffff8000103abb84)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffff8000103b6560)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffff8000103be040)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffff8000103c068c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffff8000103d0844)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/block_dev.c (ffff8000103e2734)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffff8000103e56f0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffff800010410404)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffff80001041175c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffff800010417798)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (ffff800010434048)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffff8000104493ac)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffff800010449580)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffff80001044dc38)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/configfs/inode.c (ffff800010458c68)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffff8000104598f8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffff80001045ae04)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffff80001045d4b4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffff80001045e794)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (ffff80001046c6b8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffff8000104712f4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffff800010485f14)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffff80001048bb30)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffff8000104acb90)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffff8000104c2cc4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2564)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffff8000104ea50c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffff8000104f2bc8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffff8000104f6040)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8360)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffff8000104ff368)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffff8000105064e0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffff80001050e88c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffff800010515f5c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffff800010519be8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffff80001051a744)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffff80001051c060)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffff80001051c6a8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffff8000105297e4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffff800010546160)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffff8000105555b0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffff80001146b5f0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffff8000105ae21c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffff8000105b4aa8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffff8000105b67d0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074bcdc)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffff8000108aae68)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffff8000108bece0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffff8000108f69d8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffff800010ba0e58)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (c03ac450)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (c0433e58)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (c043446c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (c044a0c8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (c04c2cc0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (c04e0d40)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (c04fdc40)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (c053ee78)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (c0566f04)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c056809c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (c056ae08)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (c0574130)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (c057b594)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (c05820f0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (c05833f4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (c0584134)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (c058cc0c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (c05948a0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (c059b894)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (c059da40)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (c05abbdc)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (c05b8a60)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (c05bd334)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (c05dcd08)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (c05ddd30)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (c05e4518)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (c05fa8e0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (c060e49c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (c060e6b8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/configfs/inode.c (c061a9d0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (c061b4a8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (c061c9c8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
  - fs/configfs/dir.c:detach_groups
```
```
In fs/configfs/symlink.c (c061e2b0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (c061f234)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (c062daa0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (c06321a0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (c0647d5c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (c064e4ac)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c0675268)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (c06877a0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/file.c (c06a842c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (c06b0378)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (c06b3908)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ecryptfs/crypto.c (c06b5c44)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (c06bc1ec)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (c06c2590)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (c06ca038)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (c06d0d04)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (c06d42a0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (c06d4be8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (c06d85e0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (c06d8d2c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (c06e4b34)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
```
In security/inode.c (c06fbf38)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (c070b08c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (c15442a4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (c075d8ac)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c0763e7c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (c07657b8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (c08ce7e4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (c09a7300)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (c09b80dc)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (c09e2a3c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (c0cc3220)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (c0000000001b7a94)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (c000000000268664)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (c00000000026911c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (c000000000288778)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (c000000000340228)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (c00000000036a868)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (c000000000395a14)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (c0000000003fe7f0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (c00000000047176c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c000000000472794)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (c000000000475494)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (c000000000483d60)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (c00000000048e690)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (c0000000004970a4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (c000000000498848)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (c00000000049998c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (c0000000004a6d28)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (c0000000004b2c80)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (c0000000004bcb08)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (c0000000004bfc90)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (c0000000004d3188)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/block_dev.c (c0000000004e84b0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (c0000000004ebb40)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (c00000000051df8c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (c00000000051f22c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (c0000000005272c0)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (c0000000005440c4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (c00000000055fed0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (c000000000560180)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (c000000000565450)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/configfs/inode.c (c0000000005739ac)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (c0000000005748cc)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (c000000000576860)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (c0000000005790d8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (c00000000057a7dc)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (c00000000058c084)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (c000000000591b80)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (c0000000005aba04)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (c0000000005b3038)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c0000000005e4d50)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (c0000000005fad70)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (c00000000061f628)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (c000000000628578)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (c0000000006329b8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (c000000000636e90)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (c00000000063a1d4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (c000000000642af4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:reconnect_path
```
```
In fs/fuse/dir.c (c00000000064b818)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (c000000000655a90)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (c00000000065eb08)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (c0000000006633a8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (c0000000006640b8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In ipc/mqueue.c (c000000000676474)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (c00000000069cb9c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (c0000000006b5958)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (c00000000139a058)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (c00000000072cf18)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c000000000737774)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (c00000000073ab0c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ada9c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (c000000000942640)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (c0000000009612d0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (c000000000991e34)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (c000000000c74f80)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffe000104c18)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffe000166ddc)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffe0001673c0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffe00016cce8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffe0001c455a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffe0001d905e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffe0001f14ba)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffe000227946)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffe00025295a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffe0002536bc)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffe0002550a2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffe00025d6e4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffe000264910)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffe000268e3a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (ffffffe000269842)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffe00026a142)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffe000271104)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffe000279202)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffe00027f488)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffe000280de2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffe00028ca82)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/block_dev.c (ffffffe000298d20)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffe00029afb2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffe0002b8d90)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffe0002b999e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffe0002bdf78)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (ffffffe0002cf88c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffe0002ded4a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffe0002deef8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffe0002e24b4)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/configfs/inode.c (ffffffe0002e9c5c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffe0002ea560)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffe0002eb714)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffe0002ed1b4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffe0002ee454)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (ffffffe0002f9bbe)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffe0002fd5ba)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffe00030e03a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffe00031281c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffe00032feda)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffe00033e466)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffe000356016)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffe00035b354)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffe000362232)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffe000364e50)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffe000366cfa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffe00036d05c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffe0003727dc)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffe000379454)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffe00037f702)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffe000382eb0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffe0003837c4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In ipc/mqueue.c (ffffffe00038dc20)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
```
```
In security/inode.c (ffffffe0003a1c62)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae0a0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffe00002665e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f64a4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffe0003fbc46)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffe0003fd40e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9a9c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffe00055fee8)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffe000571322)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffe000587824)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffe000738b9e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffff810f43fa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff811770df)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81177727)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8118bd6e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff81200aaa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8121edbe)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8123be22)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81284886)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812cf937)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812d03f1)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812d276c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812dce9a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812e5014)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff812ea88e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812eb8b3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812ec2c0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff812f475b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812fb781)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff81302bd9)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8130464a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81311e63)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/block_dev.c (ffffffff8131fe12)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81322902)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8134737a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff8134817d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff8134ceb6)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81363611)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff8137503d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff8137521d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81378810)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81380f33)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff8138194a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff81382dc0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81384343)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813851cc)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81392354)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8139647b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813a9bcc)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff813ae94d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813d1a35)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813e2d3f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc3a2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8140267f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81409e44)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff8140cee6)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f294)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81415c53)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8141b72b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81422f15)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff81429874)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8142c6ce)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8142cf0b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff8142e384)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8142e910)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81439b4b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814523ee)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8145f7cd)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828da308)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff814ae359)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b47c0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b5ed6)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b6e74)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8168052f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81699b37)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816ce40e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff818ab8aa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffff810e45da)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff8116a27f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8116a8c7)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff8117ee4e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811f37fa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81211f7e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8122ee22)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812766f6)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812c05b7)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812c1071)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812c33ec)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812cdb1a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812d5c54)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff812db4ce)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812dc4e3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812dcef0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff812e537b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812ec3a1)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff812f37f9)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812f526a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81302a73)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/block_dev.c (ffffffff813109b2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff813134a2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8133805a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81338e5d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff8133db96)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (ffffffff813542b1)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff81365b0d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81365ced)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813692e0)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813719c3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff813723da)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff81373850)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81374dd3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff81375c5c)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81382de4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81386f0b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff8139a65c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff8139f3dd)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813c24b5)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813d37bf)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813ece22)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813f30ff)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff813fa8c4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff813fd966)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813ffd14)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff814066d3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8140c1ab)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81413995)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff8141a2f4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8141d14e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8141d98b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff8141ee04)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8141f390)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8142a5bb)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff81442e3e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814501fd)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828d2a24)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8149ed79)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a51e0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a68f6)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5c54)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8165e1ff)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81677527)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816a973e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff818657fa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffff810f15fa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff81174eaf)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811754f7)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff81189b3e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811fe87a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8121cb5e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff81239bc2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81282696)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812cd747)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812ce201)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812d057c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812dacaa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812e2e24)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff812e869e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812e96c3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812ea0d0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff812f256b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812f9571)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff813009c9)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8130243a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff8130fc53)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/block_dev.c (ffffffff8131d8e2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff813203d2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81344e4a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81345c4d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff8134a986)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (ffffffff813610e1)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff81372b0d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81372ced)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813762e0)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/configfs/inode.c (ffffffff8137ea03)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff8137f41a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff81380890)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81381e13)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff81382c9c)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8138fcb4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81393ddb)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813a742c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff813ac1ad)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813ceec5)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813e00bf)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813f9722)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813ff9ff)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff814071c4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a266)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8140c614)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81412fd3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff814178cb)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8141f0b5)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff81425a14)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8142886e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff814290ab)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff8142a524)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8142aab0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81435ceb)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8144e48e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8145b86d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828ed07c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff814aa3f9)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b0850)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b1f66)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b7404)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816ae90f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff816c7da7)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816fc97e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff818fc8aa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
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
In kernel/sched/debug.c (ffffffff810fc5ea)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/audit_watch.c (ffffffff8118278f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81182dd7)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/relay.c (ffffffff811974ae)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff8120d8da)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8122bbee)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff812492b2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8129237f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812de557)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812df011)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812e13ac)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812ebbaa)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812f2d62)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
  - fs/namei.c:done_path_create
  - fs/namei.c:filename_create
  - fs/namei.c:do_last
  - fs/namei.c:kern_path_locked
```
```
In fs/fcntl.c (ffffffff812f966a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812fa6c3)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/readdir.c (ffffffff812fb0c0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/readdir.c:iterate_dir
```
```
In fs/inode.c (ffffffff81303b9b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/inode.c:unlock_two_nondirectories
  - fs/inode.c:unlock_two_nondirectories
```
```
In fs/namespace.c (ffffffff8130a88f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff81311d09)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff81313a5a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81321453)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/block_dev.c (ffffffff8132f5e2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff813320f2)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8135812a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81358f2d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/locks.c (ffffffff8135f25f)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81372ff6)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff813864ed)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813866cd)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81389d90)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81392503)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/file.c (ffffffff81392f1a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8139434c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81395940)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813967bc)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813a3b0f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813a7e6b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813bbc3c)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff813c0b4d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813e41f5)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813f54df)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f37d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8141562f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8141ce84)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/ecryptfs/mmap.c (ffffffff8141ff56)
Location: include/linux/fs.h:795
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81422294)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81428c53)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8142e6bb)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81435e35)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/debugfs/inode.c (ffffffff8143c8d4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8143f72a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8143ff6b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff814413e4)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81441970)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8144de8b)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8146585e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8147300d)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828f249e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff814c2e39)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814c92d0)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814ca9e6)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d0e74)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816c8d5f)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff816e2287)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff8171721e)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff8191d91a)
Location: include/linux/fs.h:795
Inline: True
Inline callers:
  - net/socket.c:__sock_release
```
</details>
</li>
</ul>

## Differences
