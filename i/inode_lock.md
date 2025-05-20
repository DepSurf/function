# Function: <code>inode_lock</code>

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
In kernel/sched/debug.c (ffffffff810c9228)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff811453c3)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff81189e90)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811a29d0)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff811c2c74)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff811f44a2)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
```
In fs/open.c (ffffffff8122fad6)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8123186f)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812398d6)
Location: include/linux/fs.h:735
Inline: True
```
```
In fs/namei.c (ffffffff8124174c)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:path_openat
```
```
In fs/ioctl.c (ffffffff812475d5)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff8124f7e1)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81256234)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8125aec8)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8125cb18)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81269040)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff81270657)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812741af)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812870e2)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/dax.c:dax_do_io
```
```
In fs/quota/dquot.c (ffffffff8129ed0e)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff812b0c63)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812b0f13)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff812b4328)
Location: include/linux/fs.h:735
Inline: True
```
```
In fs/devpts/inode.c (ffffffff812bb505)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
```
```
In fs/ext4/file.c (ffffffff812bfcb6)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff812ca288)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff812cf97f)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812edd20)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (ffffffff812f9c42)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/hugetlbfs/inode.c (ffffffff81328550)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8132e435)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff813354c6)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_removexattr
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff81338664)
Location: include/linux/fs.h:735
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff81341139)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff813486d9)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8134d441)
Location: include/linux/fs.h:735
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
In fs/debugfs/inode.c (ffffffff81351fd3)
Location: include/linux/fs.h:735
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81354b81)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81355467)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In fs/efivarfs/file.c (ffffffff8135693a)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81356dd9)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81361ece)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_open
```
```
In security/inode.c (ffffffff81375587)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff81381c34)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff813adad9)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/integrity/ima/ima_main.c (ffffffff813d3470)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c19c4)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8156360e)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/base/devtmpfs.c (ffffffff815a4a9a)
Location: include/linux/fs.h:735
Inline: True
Inline callers:
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
In kernel/sched/debug.c (ffffffff810cf248)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8114ec84)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff81199280)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811b2810)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff811d2cd4)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81204fd2)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
```
In fs/open.c (ffffffff81242076)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff81243e1f)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8124c616)
Location: include/linux/fs.h:688
Inline: True
```
```
In fs/namei.c (ffffffff812545cd)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:path_openat
```
```
In fs/ioctl.c (ffffffff8125a5b5)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff81262811)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81269620)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8126e468)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff81270068)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff8127c020)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff81283e27)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812884c6)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8129e85d)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/quota/dquot.c (ffffffff812b4664)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff812c65c3)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812c67b3)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff812c9bb8)
Location: include/linux/fs.h:688
Inline: True
```
```
In fs/devpts/inode.c (ffffffff812d0c8b)
Location: include/linux/fs.h:688
Inline: True
```
```
In fs/ext4/file.c (ffffffff812d4ec6)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff812dff65)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff812e579d)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81303c90)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/extents.c (ffffffff8130fc12)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e2a0)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81344165)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff8134b29d)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e40e)
Location: include/linux/fs.h:688
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff81356f60)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8135e079)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81362d51)
Location: include/linux/fs.h:688
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
In fs/debugfs/inode.c (ffffffff81368283)
Location: include/linux/fs.h:688
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8136ae41)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8136b727)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
```
```
In fs/efivarfs/file.c (ffffffff8136cd8a)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8136d2bf)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff813786ce)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_open
```
```
In security/inode.c (ffffffff8138beb7)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff813986b4)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff813c48e9)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
```
```
In security/integrity/ima/ima_main.c (ffffffff813eadf9)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e39b4)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8158fd6e)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/tpm_eventlog.c (ffffffff815a6cea)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff815d324a)
Location: include/linux/fs.h:688
Inline: True
Inline callers:
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
In kernel/sched/debug.c (ffffffff810d0381)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff81151344)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811a12d0)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811b9480)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff811db6c4)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81210691)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
```
In fs/open.c (ffffffff8124d513)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8124f63e)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8125872a)
Location: include/linux/fs.h:707
Inline: True
```
```
In fs/namei.c (ffffffff81260117)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:path_openat
```
```
In fs/fcntl.c (ffffffff81265f53)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff81266f85)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812700b8)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81276dc0)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8127bc68)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8127d76a)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81289330)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff812914f2)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812943c4)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff812ad35b)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/quota/dquot.c (ffffffff812c23f2)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff812d37c5)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812d39b5)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff812d7063)
Location: include/linux/fs.h:707
Inline: True
```
```
In fs/configfs/inode.c (ffffffff812de302)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff812df5a7)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff812e2259)
Location: include/linux/fs.h:707
Inline: True
```
```
In fs/ext4/extents.c (ffffffff812ee1d6)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff812f17d2)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff81301d34)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff8130916b)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8132b06e)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff8133bdef)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
```
```
In fs/hugetlbfs/inode.c (ffffffff81352eed)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81358c1b)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff8135fe3d)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff81362f8e)
Location: include/linux/fs.h:707
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff8136bb13)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff81372b59)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8137778e)
Location: include/linux/fs.h:707
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
In fs/debugfs/inode.c (ffffffff8137c4e0)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_lookup
```
```
In fs/tracefs/inode.c (ffffffff8137f491)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8137fefd)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff813812be)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81381823)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8138cb5f)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff813a192e)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff813aeb11)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff813d8b8c)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_create
```
```
In security/integrity/ima/ima_main.c (ffffffff813f7147)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814ef7a3)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff815a3e4e)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/tpm1_eventlog.c (ffffffff815bbaaa)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff815e7e25)
Location: include/linux/fs.h:707
Inline: True
Inline callers:
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
In kernel/sched/debug.c (ffffffff810d7d31)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8115db44)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811b4e50)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811cf900)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff811f14c4)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81227b52)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
```
```
In fs/open.c (ffffffff8126f493)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8127157e)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8127a4f1)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812827f7)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:path_openat
```
```
In fs/fcntl.c (ffffffff81288833)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff81289815)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812929f8)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81299800)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8129e708)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812a020a)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff812abe50)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff812b4242)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812b735a)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff812d167b)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/quota/dquot.c (ffffffff812e629d)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff812f8000)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812f81f0)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff812fb80c)
Location: include/linux/fs.h:711
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81302c42)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81303f27)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff81306c39)
Location: include/linux/fs.h:711
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81312c96)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff81316134)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff81328cf2)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff8132dacf)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8134f4de)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff81360299)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff81377a58)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8137d92b)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff81384afd)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff81387c2e)
Location: include/linux/fs.h:711
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff81390699)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff81397819)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8139c52e)
Location: include/linux/fs.h:711
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
In fs/debugfs/inode.c (ffffffff813a1390)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_lookup
```
```
In fs/tracefs/inode.c (ffffffff813a44e1)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff813a4f0d)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff813a62ce)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813a6833)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff813b1f0f)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff813c772e)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff813d4bc1)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff813ff179)
Location: include/linux/fs.h:711
Inline: True
```
```
In security/integrity/ima/ima_main.c (ffffffff8141f267)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:ima_file_free
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8152431f)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8160a74e)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/tpm1_eventlog.c (ffffffff81621ffa)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_teardown
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff8164f1c5)
Location: include/linux/fs.h:711
Inline: True
Inline callers:
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
In kernel/sched/debug.c (ffffffff810ddcb7)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8116caa8)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811d3cc1)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff811f0a15)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8121300d)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8124d540)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff81294126)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff81294f44)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8129727c)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812a1008)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812ab91f)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:path_openat
```
```
In fs/fcntl.c (ffffffff812aecde)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812afbb5)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812b87f9)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812bf6b0)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff812c51b8)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812c69a6)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff812d2b08)
Location: include/linux/fs.h:713
Inline: True
```
```
In fs/block_dev.c (ffffffff812db862)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812e1203)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff812fc16b)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/quota/dquot.c (ffffffff813140f8)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff81325340)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81325530)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81328e5a)
Location: include/linux/fs.h:713
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81330b95)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81331ca7)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff81334c3d)
Location: include/linux/fs.h:713
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81340b56)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff81343fc4)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff81357086)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff8135be6e)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8137d948)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff8138e29d)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6468)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813ac3a4)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff813b3917)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6892)
Location: include/linux/fs.h:713
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff813bf69f)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff813c6a83)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff813cb998)
Location: include/linux/fs.h:713
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
In fs/debugfs/inode.c (ffffffff813d0c0a)
Location: include/linux/fs.h:713
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813d3891)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff813d42ac)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff813d55df)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813d5b4b)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff813e071e)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff813f6d6e)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff81404d87)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff82717343)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
```
In security/integrity/ima/ima_main.c (ffffffff8145138a)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814565b0)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81457aba)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a06f)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81644095)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8165b9ca)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff8168ab7c)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff8186f383)
Location: include/linux/fs.h:713
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
In kernel/sched/debug.c (ffffffff810e8429)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8117a7c8)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811e41c1)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8120123b)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff81224abd)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81261955)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812a8de6)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812a9c34)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812abf2c)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812b6008)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812be52f)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:path_openat
```
```
In fs/fcntl.c (ffffffff812c3dcf)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812c4d65)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812cd949)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812d48b0)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff812da3b8)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812dbba6)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff812e7ee8)
Location: include/linux/fs.h:761
Inline: True
```
```
In fs/block_dev.c (ffffffff812f269b)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff812f4a1a)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813119db)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/quota/dquot.c (ffffffff8132b088)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff8133c4e0)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff8133c6d0)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff8133fc9a)
Location: include/linux/fs.h:761
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81347f85)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813491a7)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff8134bf88)
Location: include/linux/fs.h:761
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81358166)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/file.c (ffffffff8135c104)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff8136f3a4)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffff813741ea)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81396148)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813a688e)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf248)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813c5664)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff813ccdf7)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff813cfde2)
Location: include/linux/fs.h:761
Inline: True
```
```
In fs/exportfs/expfs.c (ffffffff813d8d50)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff813ddb00)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff813e518b)
Location: include/linux/fs.h:761
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
In fs/debugfs/inode.c (ffffffff813eb37a)
Location: include/linux/fs.h:761
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813edf21)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff813ee7fc)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff813efc2f)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813f014a)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff813faf0e)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8141281e)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8141f767)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828cee08)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
```
In security/integrity/ima/ima_main.c (ffffffff8146e385)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81473a30)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81474ff2)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8157197f)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81662365)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8167aa1a)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816aadac)
Location: include/linux/fs.h:761
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff8188f843)
Location: include/linux/fs.h:761
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
In kernel/sched/debug.c (ffffffff810f0859)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff81187618)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811fb391)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81218e2c)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8123554d)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8127c71d)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812c5908)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812c63e1)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812c873c)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812d2d88)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812db142)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (ffffffff812e07ec)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812e17b5)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812ea6f9)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812f1db7)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff812f899a)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812fa226)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff813067f8)
Location: include/linux/fs.h:776
Inline: True
```
```
In fs/block_dev.c (ffffffff81314048)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff813171e4)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81338f3f)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/quota/dquot.c (ffffffff81352c98)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff81364740)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81364920)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81367faa)
Location: include/linux/fs.h:776
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81370412)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81371b57)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/devpts/inode.c (ffffffff81374959)
Location: include/linux/fs.h:776
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8138177e)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813852c1)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813988fb)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff8139d8ba)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813c00fc)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813d1081)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9b1d)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813f019a)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff813f796c)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff813fa9d2)
Location: include/linux/fs.h:776
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813fcd89)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff814036cc)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff814097af)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81410c4d)
Location: include/linux/fs.h:776
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
In fs/debugfs/inode.c (ffffffff81417251)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8141a1d9)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8141aa9d)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff8141bf14)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8141c4c1)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff814272f0)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814404fc)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8144d3b6)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828e8894)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8149bc55)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a1730)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a2bfa)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a1e70)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81697f25)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff816b13ea)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816e49a8)
Location: include/linux/fs.h:776
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff818d98a3)
Location: include/linux/fs.h:776
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
In kernel/sched/debug.c (ffffffff810fb059)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff81193538)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff81208461)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff812266d9)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8124378d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8128c1f1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812d7318)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812d7df1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812da14c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812e4898)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812ecc52)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (ffffffff812f2298)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812f3285)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812fc129)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81303977)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8130a5ca)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8130c026)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81319864)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/block_dev.c (ffffffff81327812)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff8132a062)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8134ed66)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff8134fb5b)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff8136b01d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff8137c9d0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff8137cbb0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff8138020f)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81388902)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81389f97)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff8138be04)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff8138cbd9)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81399d2e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8139dece)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813b1385)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff813b6332)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813d93cc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813ea751)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff81403bbd)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8140a07a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8141183c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff814148a2)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81416c69)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8141d5f8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8142310f)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8142a85d)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (ffffffff81431111)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff81434049)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8143490d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff81435d64)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81436311)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81441020)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff81459dcc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814671ce)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828f1380)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff814b5d2e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814bc1c3)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814bd8ca)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c2cf0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816baa85)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff816d40ca)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81708ca8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff8190b883)
Location: include/linux/fs.h:790
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
In kernel/sched/debug.c (ffffffff81105bb9)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff811a886f)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff81230fd1)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81251681)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8127086d)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812bf10f)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff8130c288)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8130de7f)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8131076c)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8131c152)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81326aa3)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:open_last_lookups
```
```
In fs/fcntl.c (ffffffff8132a4af)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8132b9c5)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff81334c69)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff8133fa5c)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8134355c)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff81345506)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff8135380e)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (ffffffff81360af8)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81363d60)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813951c3)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff813963c8)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff813b18e6)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff813c634e)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813c652e)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813ca41f)
Location: include/linux/fs.h:808
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813d3642)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813d49b7)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff813d7126)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813d7e89)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/devpts/inode.c:mknod_ptmx
```
```
In fs/ext4/extents.c (ffffffff813e33e3)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813e9290)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff813fcfe8)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81401efb)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8142581c)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_orphan_cleanup
```
```
In fs/ext4/xattr.c (ffffffff81436206)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff81451a1c)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81457d6a)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81460102)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff8146246c)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
```
```
In fs/ecryptfs/crypto.c (ffffffff814651ce)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8146c18d)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8147257f)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8147a9a0)
Location: include/linux/fs.h:808
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
In fs/debugfs/inode.c (ffffffff81480f15)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff814836a6)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff814846e5)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff814857a9)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814860c2)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81491df0)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814ad04c)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814bba9e)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff814f0449)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff815154cf)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8151c648)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8151e1bb)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d1e0)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8176ee25)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81788457)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff817c3eb8)
Location: include/linux/fs.h:808
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff819dda73)
Location: include/linux/fs.h:808
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
In kernel/sched/debug.c (ffffffff81104209)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff811a5def)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff81215bc5)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_iter_link_pin_kernel
```
```
In kernel/events/core.c (ffffffff8123abe1)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8125ce35)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8127b919)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812cad2f)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff81318182)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8131b5df)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8131c99c)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff81327642)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81331f15)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:open_last_lookups
```
```
In fs/fcntl.c (ffffffff81335a26)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff81336fa4)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff813405d9)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff8134babc)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8134f6ec)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff81351856)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff8136013a)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/block_dev.c (ffffffff8136cad5)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81370e67)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813a6693)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff813a80e8)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff813c2ee6)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff813d82fe)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813d84ee)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813dc0df)
Location: include/linux/fs.h:771
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813e5382)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813e66d7)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff813e8dc6)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813e9b29)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/devpts/inode.c:mknod_ptmx
```
```
In fs/ext4/extents.c (ffffffff813f4bf2)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813fb690)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff8140f754)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff814147bb)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8143d19c)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_orphan_cleanup
```
```
In fs/ext4/xattr.c (ffffffff8144ec46)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff8146df3c)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff814740ba)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8147bd22)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff8147ddbc)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
```
```
In fs/ecryptfs/crypto.c (ffffffff81480a74)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff814868ac)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8148cd6e)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8149562c)
Location: include/linux/fs.h:771
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
In fs/fuse/dax.c (ffffffff8149dfa3)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff8149e6a5)
Location: include/linux/fs.h:771
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814a0d16)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff814a1d35)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff814a2db9)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814a36c3)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff814af450)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814ca59c)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814d9423)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff81bf1517)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff81532514)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff815394b8)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8153af8b)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168d900)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81789705)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8179f377)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81c0e8df)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
```
In net/socket.c (ffffffff819dd463)
Location: include/linux/fs.h:771
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
In kernel/sched/debug.c (ffffffff8110632e)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff811a66ef)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff812188f5)
Location: include/linux/fs.h:772
Inline: True
```
```
In kernel/events/core.c (ffffffff8123f3b1)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81261ab5)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff81280a79)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812d180d)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff8131e371)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8132171e)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff81322b0c)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8132f8f9)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff81335fb1)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:open_last_lookups
```
```
In fs/fcntl.c (ffffffff8133bb96)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8133d1c4)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff81346b09)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff8135234f)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff813561f1)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff81358576)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff81366bc9)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/block_dev.c (ffffffff81373375)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81377814)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813ad72a)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff813af13c)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff813ca14b)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff813df19e)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff813df37e)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813e307f)
Location: include/linux/fs.h:772
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813ebf92)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813ed0e7)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff813ef936)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813f07b9)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff813faf32)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81401b5a)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff81415ad4)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff8141b2ea)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81442fdc)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_orphan_cleanup
```
```
In fs/ext4/xattr.c (ffffffff81455aea)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff814736eb)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81479a29)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff814815b2)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff814841a2)
Location: include/linux/fs.h:772
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81486351)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8148c2fa)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff814925cd)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8149a68c)
Location: include/linux/fs.h:772
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
In fs/fuse/dax.c (ffffffff814a3f73)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff814a4671)
Location: include/linux/fs.h:772
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814a6e46)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff814a7e65)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff814a9000)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814a96a5)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff814b5290)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814d0bcc)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814dfb13)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff831fe2aa)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8153a994)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81541bb8)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8154365b)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816705f0)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8176cfe5)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81782015)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff817bcfc3)
Location: include/linux/fs.h:772
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff819c36b3)
Location: include/linux/fs.h:772
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
In kernel/sched/debug.c (ffffffff81123e8a)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff811cfedf)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff8124ef2b)
Location: include/linux/fs.h:784
Inline: True
```
```
In kernel/events/core.c (ffffffff81279f21)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8129a3c5)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff812bee99)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81316f20)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff8136b744)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff8136ebfe)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff8136fffc)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8137d0a9)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff813836b4)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:open_last_lookups
```
```
In fs/fcntl.c (ffffffff81389814)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8138ac73)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/inode.c (ffffffff81394569)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff813a0715)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff813a4721)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff813a6bb6)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff813b5719)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff813c3d73)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813fd0aa)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff813fecec)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff8141a8eb)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff81430b4e)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81430d2e)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81434b8f)
Location: include/linux/fs.h:784
Inline: True
```
```
In fs/configfs/inode.c (ffffffff8143dd3c)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8143efe7)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81441826)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff814426a9)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff8144d318)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814540ea)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff81468fef)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff8146e5f3)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81496c8a)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff814a9b0a)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff814b191e)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca319)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff814d100e)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff814d9372)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff814db822)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff814ddae1)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff814e3b0a)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff814ea14d)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff814f20f3)
Location: include/linux/fs.h:784
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
In fs/fuse/dax.c (ffffffff814fbfc1)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff814fc6f1)
Location: include/linux/fs.h:784
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814fefa6)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81500165)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff815014ba)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81501a35)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8150d950)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff815298fc)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff81538a91)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff832e55bc)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff81599346)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff815a1978)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff815a3d91)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff815c5995)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e48c0)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff817f27b5)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff818088b8)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81847343)
Location: include/linux/fs.h:784
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81a72f43)
Location: include/linux/fs.h:784
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
In kernel/sched/build_utility.c (ffffffff8113d3b3)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8120444c)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff81295faf)
Location: include/linux/fs.h:739
Inline: True
```
```
In kernel/events/core.c (ffffffff812cd316)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff812f73e5)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8131ab2b)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81382544)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff813e98ae)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff813ed481)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff813eea2c)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff813f9d95)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81404156)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:open_last_lookups
```
```
In fs/fcntl.c (ffffffff8140a4f8)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8140bee3)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/inode.c (ffffffff814164f0)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff81424030)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff81428741)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff8142b852)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff8143a9fc)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff8144aba3)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81470832)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81472880)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff81490acb)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff814aa89e)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff814aaa8e)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff814aece7)
Location: include/linux/fs.h:739
Inline: True
```
```
In fs/configfs/inode.c (ffffffff814b962c)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff814bb147)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff814bd429)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff814be434)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff814c9da7)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814d1658)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff814e8dc3)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff814eef69)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81521c10)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff81531e02)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff8153a46a)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff815560b3)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8155dbd7)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81566b82)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff815693f2)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff8156bba7)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81571ee4)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff81578a81)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81581a6e)
Location: include/linux/fs.h:739
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
In fs/fuse/dax.c (ffffffff8158c531)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff8158ce14)
Location: include/linux/fs.h:739
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8158ffa6)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81591325)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff81592807)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81592e4e)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff815a0382)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff815bf11b)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff815d003e)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff8349c325)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8163df8e)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81647d33)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8164a79c)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff816701e5)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f21f)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81933265)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8194880f)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff8198be2f)
Location: include/linux/fs.h:739
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81be58a3)
Location: include/linux/fs.h:739
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
In kernel/sched/build_utility.c (ffffffff81167e03)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8124c32c)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff812f0e3f)
Location: include/linux/fs.h:754
Inline: True
```
```
In kernel/events/core.c (ffffffff813353b6)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81360c95)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8138e8ee)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff813fc49f)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff814718ce)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff81475a89)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff814772fc)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff8148368e)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8148e5d6)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:open_last_lookups
```
```
In fs/fcntl.c (ffffffff81494d81)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff81496903)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/inode.c (ffffffff814a18e0)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff814b077c)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff814b5c71)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff814b8922)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff814c8eac)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff814d92e0)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff815022d2)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81504570)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/posix_acl.c (ffffffff81515f33)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff8152467b)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff8154050e)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff8154072e)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81545387)
Location: include/linux/fs.h:754
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81550dbc)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81552a77)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81555099)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff81556214)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff81562425)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8156a46f)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff815828d2)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff815890f8)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff815be708)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff815ce89e)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff815d89ea)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff815f77ab)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff815ffc57)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8160a152)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff8160cf92)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff8160fbd6)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81617314)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8161e041)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff816278ee)
Location: include/linux/fs.h:754
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
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff81632de3)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff816337a4)
Location: include/linux/fs.h:754
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81637346)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/tracefs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81638925)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff8163a097)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8163a88c)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81649ce2)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8166b50b)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8167dd2e)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff83ed3508)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff816f5bb8)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81700573)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff817038ec)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff8172b785)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193df5f)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81a91fb5)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81aabc9f)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81afb88e)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81d91b23)
Location: include/linux/fs.h:754
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
In kernel/sched/build_utility.c (ffffffff811784c6)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8126364f)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff8131daef)
Location: include/linux/fs.h:769
Inline: True
```
```
In kernel/events/core.c (ffffffff81366109)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81393055)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff813c1cc1)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff8142f7b2)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff814a6216)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff814aa426)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff814abc5f)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff814bb59b)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814c3540)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:open_last_lookups
```
```
In fs/fcntl.c (ffffffff814ca10e)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff814cb943)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/namespace.c (ffffffff814e57a9)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_lock_mount
```
```
In fs/xattr.c (ffffffff814ea4bf)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff814edb32)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff814ff0ed)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff8151205c)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81539975)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff8153bd1f)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/posix_acl.c (ffffffff8154d8a3)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff8155caa1)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff815788ce)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81578aee)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff8157cf67)
Location: include/linux/fs.h:769
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81588a9c)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8158a7fa)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff8158ce39)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff8158dfc4)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff8159a188)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815a23cb)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff815b94c3)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff815bf91e)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff815f5418)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff8160616e)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff8161058a)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f78a)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff81637c3d)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81642012)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff81644e45)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff81647a66)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8164f406)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff81656171)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8165fcc4)
Location: include/linux/fs.h:769
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
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff8166b099)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff8166baa4)
Location: include/linux/fs.h:769
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8166fd23)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff81670d25)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff816724f7)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81672e66)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81682242)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff816a3c6b)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff816b5f1d)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff836f8582)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8172fdca)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8173a606)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8173d91c)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff81767605)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81982342)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81add845)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81af74ff)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81b49c7d)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81dffe05)
Location: include/linux/fs.h:769
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
In kernel/sched/build_utility.c (ffffffff811861e6)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8127d3df)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/bpf/inode.c (ffffffff8133feff)
Location: include/linux/fs.h:802
Inline: True
```
```
In kernel/events/core.c (ffffffff8138f229)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff813bcd05)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff813eca41)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
  - mm/shmem.c:shmem_file_write_iter
```
```
In mm/swapfile.c (ffffffff8146938d)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff814d7166)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff814db8c6)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff814dd0ff)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff814edb0b)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814f6225)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:open_last_lookups
```
```
In fs/fcntl.c (ffffffff814fc9dc)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff814fe1f3)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
```
In fs/inode.c (ffffffff81508ead)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff815195d9)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_lock_mount
```
```
In fs/xattr.c (ffffffff8151e35f)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff81521892)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/utimes.c (ffffffff81533d1d)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/direct-io.c (ffffffff81546538)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff8156eb75)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81570fff)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/posix_acl.c (ffffffff815836d3)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff8159325e)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:vfs_cleanup_quota_inode
```
```
In fs/proc/self.c (ffffffff815b105e)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff815b12ce)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff815b58b6)
Location: include/linux/fs.h:802
Inline: True
```
```
In fs/configfs/inode.c (ffffffff815c166f)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff815c34ca)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff815c5b82)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff815c6d11)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/extents.c (ffffffff815d2fd8)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815db0fb)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_checks
  - fs/ext4/file.c:ext4_buffered_write_iter
```
```
In fs/ext4/inode.c (ffffffff815f2243)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff815f86c4)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8162dd71)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
```
```
In fs/ext4/xattr.c (ffffffff8163eea1)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/ext4/orphan.c (ffffffff8164934a)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_process_orphan
```
```
In fs/hugetlbfs/inode.c (ffffffff81668c66)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8167112d)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8167b635)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_setxattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e355)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff81680f19)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff8168899c)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In fs/fuse/dir.c (ffffffff8168f9f1)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81699b24)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_file_llseek
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_cache_write_iter
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_open_common
```
```
In fs/fuse/dax.c (ffffffff816a53d9)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
```
```
In fs/debugfs/inode.c (ffffffff816a5e54)
Location: include/linux/fs.h:802
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff816aa703)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff816acc65)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_put_backend_records
```
```
In fs/efivarfs/file.c (ffffffff816ae537)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff816af208)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff816be642)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff816e06cb)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff816f30a8)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff8392b96d)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff81770758)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8177b146)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8177e77b)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In block/fops.c (ffffffff817a93f5)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - block/fops.c:blkdev_llseek
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9822)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff81b30c75)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81b4aaef)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81ba206d)
Location: include/linux/fs.h:802
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff81ebc2a5)
Location: include/linux/fs.h:802
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
In kernel/sched/debug.c (ffff800010160ce4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffff80001020c1fc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffff800010291d08)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffff8000102b3a24)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffff8000102d5a40)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffff8000103278dc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffff80001037c50c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffff80001037d1ac)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffff80001037f5c4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffff80001038c150)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffff80001039637c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (ffff80001039c370)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffff80001039dfec)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffff8000103abb08)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffff8000103b6fc4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffff8000103be010)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffff8000103c0644)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffff8000103d0828)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/block_dev.c (ffff8000103e271c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffff8000103e55e4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffff8000104103d4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffff800010411738)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffff80001043402c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffff800010449338)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffff80001044950c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffff80001044dc1c)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/configfs/inode.c (ffff800010458c1c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffff80001045a46c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffff80001045d53c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffff80001045e780)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (ffff80001046c674)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffff8000104712b8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffff800010485cec)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffff80001048bafc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffff8000104acb04)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffff8000104c2cac)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2390)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffff8000104ea494)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffff8000104f2b9c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffff8000104f5fd8)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8324)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffff8000104ff318)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffff8000105064a0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffff80001050e7f4)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (ffff800010515d78)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffff800010519b40)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffff80001051a728)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffff80001051c028)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffff80001051c698)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffff8000105294d8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffff800010546120)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffff800010555598)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffff80001146b52c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffff8000105ae1f4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffff8000105b4a90)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffff8000105b67a8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074bcac)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffff8000108aae34)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffff8000108becd0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffff8000108f69c4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffff800010ba0e38)
Location: include/linux/fs.h:790
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
In kernel/sched/debug.c (c03ac3f0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (c0449ef4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (c04c2c94)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (c04e0c94)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (c04fdbf0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (c053ecbc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (c0566e40)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c0568074)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (c056ad10)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (c0574114)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (c057b7e0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (c05820d8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (c05833b0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (c058cbac)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (c0595698)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (c059b864)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (c059d9ec)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (c05abbbc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/utimes.c:utimes_common
```
```
In fs/block_dev.c (c05b8a1c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (c05bd2e4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (c05dccd0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (c05ddcfc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (c05fa8c4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (c060e408)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (c060e624)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/configfs/inode.c (c061a97c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c061c218)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
  - fs/configfs/dir.c:detach_groups
```
```
In fs/configfs/symlink.c (c061e32c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (c061f224)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (c062da4c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (c0632054)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (c0647a50)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (c064d4d8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c06751dc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (c0687788)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_write
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/file.c (c06a8384)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (c06b034c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (c06b3860)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ecryptfs/crypto.c (c06b5bf4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (c06bc290)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (c06c2540)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (c06c9f84)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (c06d0b10)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (c06d41f0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (c06d4bcc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (c06d85ac)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (c06d8cf0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (c06e47f8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_open
```
```
In security/inode.c (c06fbef0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (c070b04c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (c15441d8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (c075d884)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c0763e64)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (c0765798)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (c08ce7b0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (c09a7298)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (c09b80c8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (c09e2a28)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (c0cc31f8)
Location: include/linux/fs.h:790
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
In kernel/sched/debug.c (c0000000001b79fc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (c000000000288550)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (c0000000003401ec)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (c00000000036a7c8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (c0000000003959a8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (c0000000003fe644)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (c000000000471714)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (c00000000047276c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (c000000000475430)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (c000000000483d38)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (c00000000048e774)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (c000000000497088)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (c000000000498804)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (c0000000004a6cb0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (c0000000004b3978)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (c0000000004bcad0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (c0000000004bfc30)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (c0000000004d3160)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/block_dev.c (c0000000004e8494)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (c0000000004eb880)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (c00000000051df54)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (c00000000051f1f0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (c0000000005440a4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (c00000000055fe38)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (c0000000005600e8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (c000000000565430)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/configfs/inode.c (c000000000573744)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c000000000575d7c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (c000000000579174)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (c00000000057a7c8)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (c00000000058c03c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (c000000000591bd8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (c0000000005ab77c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (c0000000005b2ffc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (c0000000005e4ca0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (c0000000005fad50)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (c00000000061f3fc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (c0000000006284cc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (c000000000632964)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (c000000000636e1c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (c00000000063a198)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (c000000000642ab4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:reconnect_path
```
```
In fs/fuse/dir.c (c00000000064b7d0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (c0000000006559bc)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (c00000000065e868)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (c0000000006632c0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (c000000000664094)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In ipc/mqueue.c (c000000000675e00)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (c00000000069cb44)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (c0000000006b5930)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (c000000001399f50)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (c00000000072ced4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c000000000737758)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (c00000000073aadc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ada5c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (c0000000009425d8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (c0000000009612b8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (c000000000991e14)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (c000000000c74f4c)
Location: include/linux/fs.h:790
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
In kernel/sched/debug.c (ffffffe000104bb4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffe00016cb56)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffe0001c452a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffe0001d8ff0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffe0001f1484)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffe00022774e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffe0002528dc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffe00025364c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffe000255064)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffe00025d6d6)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffe0002649ae)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (ffffffe000268e2c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (ffffffe000269818)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffe0002710b6)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffe000279bf0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffe00027f45c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffe000280d9e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffe00028ca62)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/block_dev.c (ffffffe000298d0a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffe00029af26)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffe0002b8d3c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffe0002b997a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffe0002cf87a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffe0002deccc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffe0002dee7a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffe0002e24a2)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/configfs/inode.c (ffffffe0002e9c1e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffe0002eaf10)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffe0002ed236)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffe0002ee430)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (ffffffe0002f9b8a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffe0002fd548)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffe00030de68)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/ioctl.c (ffffffe0003127d6)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffe00032fe54)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffe00033e456)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffe000355ecc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffe00035b2ee)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffe000362218)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffe000364db6)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffe000366ccc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffe00036d020)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffe0003727a4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffe0003793b4)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (ffffffe00037f538)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffe000382dfe)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffe0003837a6)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In ipc/mqueue.c (ffffffe00038d95c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_open
```
```
In security/inode.c (ffffffe0003a1c26)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae084)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffe000026582)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f647e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffe0003fbc2a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffe0003fd3de)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9a6a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffe00055febe)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffe000571314)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffe0005877fa)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffe000738b88)
Location: include/linux/fs.h:790
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
In kernel/sched/debug.c (ffffffff810f4389)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8118bb58)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff81200a81)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8121ed29)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8123bddd)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812847d1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812cf8f8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812d03d1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812d272c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812dce78)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812e5232)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (ffffffff812ea878)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812eb865)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812f4709)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812fbf57)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff81302baa)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff81304606)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81311e44)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/block_dev.c (ffffffff8131fdf2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81322642)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81347346)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff8134813b)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff813635fd)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff81374fb0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81375190)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813787ef)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81380ee2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81382577)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff813843e4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813851b9)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8139230e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813964ae)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813a9965)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff813ae912)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813d19ac)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813e2d31)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc19d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8140265a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff81409e1c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff8140ce82)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f249)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81415bd8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8141b6ef)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81422e3d)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (ffffffff814296f1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8142c629)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8142ceed)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff8142e344)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8142e8f1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff81439600)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff814523ac)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8145f7ae)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828da234)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff814ae30e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b47a3)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b5eaa)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b6e40)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816804e5)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff81699b1a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816ce3f8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff818ab883)
Location: include/linux/fs.h:790
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
In kernel/sched/debug.c (ffffffff810e4569)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff8117ec38)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811f37d1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff81211ee9)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8122eddd)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff81276641)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812c0578)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812c1051)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812c33ac)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812cdaf8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812d5e72)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (ffffffff812db4b8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812dc495)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812e5329)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812ecb77)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff812f37ca)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff812f5226)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81302a54)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/block_dev.c (ffffffff81310992)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff813131e2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81338026)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81338e1b)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff8135429d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff81365a80)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81365c60)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813692bf)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81371972)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81373007)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81374e74)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff81375c49)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81382d9e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81386f3e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff8139a3f5)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff8139f3a2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813c242c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813d37b1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecc1d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813f30da)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff813fa89c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff813fd902)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813ffcc9)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81406658)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8140c16f)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff814138bd)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (ffffffff8141a171)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8141d0a9)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8141d96d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff8141edc4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8141f371)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8142a070)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff81442dfc)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff814501de)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828d2950)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff8149ed2e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a51c3)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a68ca)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5c20)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff8165e1b5)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff8167750a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816a9728)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff818657d3)
Location: include/linux/fs.h:790
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
In kernel/sched/debug.c (ffffffff810f1589)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff81189928)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff811fe851)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8121cac9)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff81239b7d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812825e1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812cd708)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812ce1e1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812d053c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812dac88)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812e3042)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (ffffffff812e8688)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812e9675)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff812f2519)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff812f9d47)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff8130099a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff813023f6)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff8130fc34)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/block_dev.c (ffffffff8131d8c2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81320112)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff81344e16)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81345c0b)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff813610cd)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff81372a80)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81372c60)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff813762bf)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/configfs/inode.c (ffffffff8137e9b2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81380047)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff81381eb4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff81382c89)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8138fc6e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81393e0e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813a71c5)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff813ac172)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813cee3c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813e00b1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff813f951d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff813ff9da)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8140719c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a202)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8140c5c9)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81412f58)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8141788f)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff8141efdd)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (ffffffff81425891)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff814287c9)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8142908d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff8142a4e4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8142aa91)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff814357a0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8144e44c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff8145b84e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828ecfa8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff814aa3ae)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b0833)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b1f3a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b73d0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816ae8c5)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff816c7d8a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff816fc968)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff818fc883)
Location: include/linux/fs.h:790
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
In kernel/sched/debug.c (ffffffff810fc579)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/relay.c (ffffffff81197298)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/events/core.c (ffffffff8120d8b1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_fasync
```
```
In mm/filemap.c (ffffffff8122bb59)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_write_iter
```
```
In mm/shmem.c (ffffffff8124926d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_llseek
```
```
In mm/swapfile.c (ffffffff812922cf)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In mm/memfd.c (ffffffff812de518)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/open.c (ffffffff812deff1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
```
```
In fs/read_write.c (ffffffff812e136c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/read_write.c:default_llseek
```
```
In fs/exec.c (ffffffff812ebb88)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exec.c:prepare_binprm
```
```
In fs/namei.c (ffffffff812f2f80)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_last
```
```
In fs/fcntl.c (ffffffff812f9654)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff812fa675)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ioctl.c:generic_block_fiemap
```
```
In fs/inode.c (ffffffff81303b49)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/namespace.c (ffffffff8130b097)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/namespace.c:lock_mount
```
```
In fs/xattr.c (ffffffff81311cda)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/xattr.c:vfs_removexattr
  - fs/xattr.c:vfs_setxattr
```
```
In fs/libfs.c (ffffffff81313a16)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/libfs.c:__generic_file_fsync
```
```
In fs/utimes.c (ffffffff81321434)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/block_dev.c (ffffffff8132f5c2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:block_llseek
```
```
In fs/direct-io.c (ffffffff81331e32)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/policy.c (ffffffff813580f6)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (ffffffff81358eeb)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/quota/dquot.c (ffffffff81372fe2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/proc/self.c (ffffffff81386460)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81386640)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/kcore.c (ffffffff81389d6f)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813924b2)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81393b37)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_depend_item_unlocked
  - fs/configfs/dir.c:configfs_depend_item
```
```
In fs/configfs/symlink.c (ffffffff813959d0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/devpts/inode.c (ffffffff813967a9)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813a3ac9)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813a7e9e)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
```
In fs/ext4/inode.c (ffffffff813bb9d5)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO_write
```
```
In fs/ext4/ioctl.c (ffffffff813c0b12)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff813e416c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_quota_on
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/xattr.c (ffffffff813f54d1)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f17d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/fat/file.c (ffffffff8141560a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fat/file.c:fat_fallocate
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/inode.c (ffffffff8141ce5c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_listxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
```
In fs/ecryptfs/mmap.c (ffffffff8141fef2)
Location: include/linux/fs.h:790
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81422249)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
```
```
In fs/exportfs/expfs.c (ffffffff81428bd8)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
```
In fs/fuse/dir.c (ffffffff8142e67f)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dir_fsync
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/fuse/file.c (ffffffff81435d5d)
Location: include/linux/fs.h:790
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
In fs/debugfs/inode.c (ffffffff8143c751)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/debugfs/inode.c:start_creating
```
```
In fs/tracefs/inode.c (ffffffff8143f689)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
  - fs/tracefs/inode.c:tracefs_syscall_mkdir
```
```
In fs/pstore/inode.c (ffffffff8143ff4d)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_records
```
```
In fs/efivarfs/file.c (ffffffff814413a4)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81441951)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In ipc/mqueue.c (ffffffff8144d7e0)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_open
```
```
In security/inode.c (ffffffff8146581c)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
```
In security/selinux/selinuxfs.c (ffffffff81472fee)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/apparmor/apparmorfs.c (ffffffff828f23ca)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
```
In security/integrity/ima/ima_main.c (ffffffff814c2dee)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814c92b3)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814ca9ba)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d0e40)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/char/mem.c (ffffffff816c8d15)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_lseek
```
```
In drivers/char/tpm/eventlog/common.c (ffffffff816e226a)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
```
```
In drivers/base/devtmpfs.c (ffffffff81717208)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:handle_remove
```
```
In net/socket.c (ffffffff8191d8f3)
Location: include/linux/fs.h:790
Inline: True
Inline callers:
  - net/socket.c:__sock_release
```
</details>
</li>
</ul>

## Differences
