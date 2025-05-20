# Function: <code>current_kernel_time64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct timespec current_kernel_time64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4630)
Location: kernel/time/timekeeping.c:2155
Inline: False
Direct callers:
  - kernel/time/time.c:current_fs_time
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/audit.c:audit_log_start
  - kernel/auditsc.c:__audit_syscall_entry
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
  - fs/pipe.c:create_pipe_files
  - fs/libfs.c:mount_pseudo
  - fs/libfs.c:simple_link
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:alloc_anon_inode
  - fs/nsfs.c:ns_get_path
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_add_one
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/super.c:ext4_quota_off
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fuse/control.c:fuse_ctl_add_dentry
  - fs/debugfs/inode.c:debugfs_get_inode
  - fs/tracefs/inode.c:tracefs_get_inode
  - fs/pstore/inode.c:pstore_get_inode
  - fs/efivarfs/inode.c:efivarfs_get_inode
  - ipc/mqueue.c:mqueue_read_file
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/mqueue.c:mqueue_unlink
  - ipc/mqueue.c:mqueue_create
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_notify
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_reject_and_link
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/inode.c:securityfs_create_file
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff810f4630-ffffffff810f466a: current_kernel_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timespec current_kernel_time64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fb840)
Location: kernel/time/timekeeping.c:2160
Inline: False
Direct callers:
  - kernel/time/time.c:current_fs_time
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/audit.c:audit_log_start
  - kernel/auditsc.c:__audit_syscall_entry
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
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_link
  - fs/libfs.c:mount_pseudo
  - fs/nsfs.c:ns_get_path
  - fs/posix_acl.c:simple_set_acl
  - fs/proc/inode.c:proc_get_inode
  - fs/proc/inode.c:proc_alloc_inode
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/self.c:proc_setup_self
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/proc_sysctl.c:proc_sys_make_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/super.c:ext4_quota_off
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_symlink
  - fs/hugetlbfs/inode.c:hugetlbfs_mknod
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/fuse/control.c:fuse_ctl_add_dentry
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
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/inode.c:__securityfs_setup_d_inode
  - security/selinux/selinuxfs.c:sel_make_inode
  - security/apparmor/apparmorfs.c:__aa_fs_profile_migrate_dents
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
**Symbols:**

```
ffffffff810fb840-ffffffff810fb879: current_kernel_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timespec current_kernel_time64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fe640)
Location: kernel/time/timekeeping.c:2172
Inline: False
Direct callers:
  - kernel/time/time.c:current_fs_time
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/inode.c:current_time
  - fs/jbd2/commit.c:journal_submit_commit_record
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
  - security/inode.c:__securityfs_setup_d_inode
```
**Symbols:**

```
ffffffff810fe640-ffffffff810fe679: current_kernel_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timespec current_kernel_time64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811009b0)
Location: kernel/time/timekeeping.c:2161
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - fs/inode.c:current_time
  - fs/jbd2/commit.c:journal_submit_commit_record
  - security/keys/gc.c:key_garbage_collector
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_set_timeout
  - security/keys/key.c:key_reject_and_link
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/proc.c:proc_keys_show
```
**Symbols:**

```
ffffffff811009b0-ffffffff811009ed: current_kernel_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timespec current_kernel_time64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b7a0)
Location: kernel/time/timekeeping.c:2190
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
  - kernel/auditsc.c:__audit_syscall_entry
  - fs/inode.c:current_time
  - fs/jbd2/commit.c:journal_submit_commit_record
```
**Symbols:**

```
ffffffff8110b7a0-ffffffff8110b7dd: current_kernel_time64 (STB_GLOBAL)
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
In kernel/time/posix-timers.c (ffffffff8111e584)
Location: include/linux/timekeeping.h:257
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_coarse
```
```
In kernel/audit.c (ffffffff81150282)
Location: include/linux/timekeeping.h:257
Inline: True
```
```
In kernel/auditsc.c (ffffffff811572a8)
Location: include/linux/timekeeping.h:257
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In fs/inode.c (ffffffff812b8c73)
Location: include/linux/timekeeping.h:257
Inline: True
Inline callers:
  - fs/inode.c:current_time
```
```
In fs/jbd2/commit.c (ffffffff81395495)
Location: include/linux/timekeeping.h:257
Inline: True
Inline callers:
  - fs/jbd2/commit.c:journal_submit_commit_record
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
