# Function: <code>current_kernel_time</code>

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
In kernel/time/time.c (ffffffff810eb08d)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - kernel/time/time.c:current_fs_time
```
```
In kernel/time/posix-timers.c (ffffffff810f0b3d)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
```
```
In kernel/audit.c (ffffffff811219b6)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/auditsc.c (ffffffff81128616)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/bpf/inode.c (ffffffff81176cb3)
Location: include/linux/timekeeping.h:25
Inline: True
```
```
In mm/shmem.c (ffffffff811a727d)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_mknod
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_truncate_range
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_symlink
```
```
In fs/pipe.c (ffffffff81215bdc)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/pipe.c:create_pipe_files
```
```
In fs/libfs.c (ffffffff81233b5f)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/libfs.c:mount_pseudo
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:alloc_anon_inode
```
```
In fs/nsfs.c (ffffffff81242371)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
```
```
In fs/posix_acl.c (ffffffff8126e9bf)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_set_acl
```
```
In fs/proc/inode.c (ffffffff812797a3)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/inode.c:proc_get_inode
```
```
In fs/proc/base.c (ffffffff8127d670)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/self.c (ffffffff81283c3b)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff81283ebb)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/proc_sysctl.c (ffffffff812842f8)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In fs/kernfs/inode.c (ffffffff81288c1f)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/kernfs/dir.c (ffffffff8128a144)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_add_one
```
```
In fs/devpts/inode.c (ffffffff8128e0c7)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/ext4/super.c (ffffffff812ac63d)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
```
```
In fs/jbd2/commit.c (ffffffff812e9aa2)
Location: include/linux/timekeeping.h:25
Inline: True
```
```
In fs/ramfs/inode.c (ffffffff812f3296)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_symlink
```
```
In fs/hugetlbfs/inode.c (ffffffff812f45c8)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/control.c (ffffffff8131ca72)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
```
In fs/debugfs/inode.c (ffffffff8131d3c2)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_get_inode
```
```
In fs/tracefs/inode.c (ffffffff8131eeb2)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_get_inode
```
```
In fs/pstore/inode.c (ffffffff8131f982)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_inode
```
```
In fs/efivarfs/inode.c (ffffffff81320d50)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_get_inode
```
```
In ipc/mqueue.c (ffffffff8132c153)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
```
```
In security/keys/gc.c (ffffffff8132ef0d)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8132f4c5)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_reject_and_link
```
```
In security/keys/keyring.c (ffffffff813316ae)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/keys/permission.c (ffffffff813337f3)
Location: include/linux/timekeeping.h:25
Inline: True
```
```
In security/keys/process_keys.c (ffffffff813340c0)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff81335ecb)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/inode.c (ffffffff8133fddb)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - security/inode.c:securityfs_create_file
```
```
In security/selinux/selinuxfs.c (ffffffff8134a020)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_inode
```
```
In security/apparmor/apparmorfs.c (ffffffff813763bc)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents
```
```
In drivers/usb/core/devio.c (ffffffff8161cadb)
Location: include/linux/timekeeping.h:25
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
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
In kernel/time/time.c (ffffffff810f1d5d)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/time/time.c:current_fs_time
```
```
In kernel/time/posix-timers.c (ffffffff810f7b5d)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
```
```
In kernel/audit.c (ffffffff811298e2)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
```
```
In kernel/auditsc.c (ffffffff811307c8)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/bpf/inode.c (ffffffff8118576f)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_get_inode
```
```
In mm/shmem.c (ffffffff811c1bc5)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
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
```
```
In fs/pipe.c (ffffffff8123ca47)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/pipe.c:create_pipe_files
```
```
In fs/libfs.c (ffffffff8125cc36)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo
```
```
In fs/nsfs.c (ffffffff8126a6d1)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
```
```
In fs/posix_acl.c (ffffffff8129a11f)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_set_acl
```
```
In fs/proc/inode.c (ffffffff812a68b8)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/proc/base.c (ffffffff812aa64d)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/self.c (ffffffff812b0cbb)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
```
```
In fs/proc/thread_self.c (ffffffff812b0f6b)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
```
```
In fs/proc/proc_sysctl.c (ffffffff812b13d8)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
```
```
In fs/devpts/inode.c (ffffffff812bba3f)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_mount
```
```
In fs/ext4/super.c (ffffffff812e0c5d)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_off
```
```
In fs/ramfs/inode.c (ffffffff81326c3a)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In fs/hugetlbfs/inode.c (ffffffff81327822)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/control.c (ffffffff81351572)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_ctl_add_dentry
```
```
In fs/tracefs/inode.c (ffffffff81354362)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_get_inode
```
```
In fs/pstore/inode.c (ffffffff81354e32)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_get_inode
```
```
In fs/efivarfs/inode.c (ffffffff813563b0)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_get_inode
```
```
In ipc/mqueue.c (ffffffff81360fb6)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:mqueue_get_inode
```
```
In security/keys/gc.c (ffffffff81363c66)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff81364228)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
```
```
In security/keys/keyring.c (ffffffff8136669c)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/permission.c (ffffffff81368683)
Location: include/linux/timekeeping.h:41
Inline: True
```
```
In security/keys/process_keys.c (ffffffff81368fc1)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff8136ae8b)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/inode.c (ffffffff813752fa)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/inode.c:__securityfs_setup_d_inode
```
```
In security/selinux/selinuxfs.c (ffffffff8137fd70)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_inode
```
```
In security/apparmor/apparmorfs.c (ffffffff813ae8a7)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents
```
```
In drivers/usb/core/devio.c (ffffffff8167d1d0)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
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
In kernel/time/time.c (ffffffff810f8edd)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/time/time.c:current_fs_time
```
```
In kernel/time/posix-timers.c (ffffffff811054fd)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
```
```
In kernel/audit.c (ffffffff81133551)
Location: include/linux/timekeeping.h:41
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113a538)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d6bf)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In fs/inode.c (ffffffff81262e53)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - fs/inode.c:current_time
```
```
In security/keys/gc.c (ffffffff8137a486)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8137aa48)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
```
```
In security/keys/keyring.c (ffffffff8137cebc)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/permission.c (ffffffff8137ee93)
Location: include/linux/timekeeping.h:41
Inline: True
```
```
In security/keys/process_keys.c (ffffffff8137f7d1)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff8138169b)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/inode.c (ffffffff8138bc2a)
Location: include/linux/timekeeping.h:41
Inline: True
Inline callers:
  - security/inode.c:__securityfs_setup_d_inode
```
```
In security/apparmor/apparmorfs.c (ffffffff82000b7b)
Location: include/linux/timekeeping.h:41
Inline: True
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
In fs/inode.c (ffffffff812706f5)
Location: include/linux/timekeeping.h:30
Inline: True
Inline callers:
  - fs/inode.c:current_time
```
```
In security/keys/gc.c (ffffffff8138e068)
Location: include/linux/timekeeping.h:30
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (ffffffff8138e64a)
Location: include/linux/timekeeping.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
```
```
In security/keys/keyring.c (ffffffff81390c50)
Location: include/linux/timekeeping.h:30
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/permission.c (ffffffff81392df5)
Location: include/linux/timekeeping.h:30
Inline: True
```
```
In security/keys/process_keys.c (ffffffff813936dd)
Location: include/linux/timekeeping.h:30
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff813955fb)
Location: include/linux/timekeeping.h:30
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293033)
Location: include/linux/timekeeping32.h:15
Inline: True
Inline callers:
  - fs/inode.c:current_time
```
</details>
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
In <code>6.8</code>: Absent ⚠️
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
