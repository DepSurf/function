# Function: <code>audit_dummy_context</code>

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
In kernel/capability.c (ffffffff8108a63b)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
```
```
In kernel/ptrace.c (ffffffff8108adf9)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff8108d0e6)
Location: include/linux/audit.h:146
Inline: True
```
```
In kernel/auditsc.c (ffffffff811295fd)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_signal_info
```
```
In kernel/audit_watch.c (ffffffff81129f58)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/seccomp.c (ffffffff8113be26)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_phase2
```
```
In mm/mmap.c (ffffffff811c5b17)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In fs/open.c (ffffffff8120aea9)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - fs/open.c:SyS_fchmod
  - fs/open.c:SyS_fchown
```
```
In fs/exec.c (ffffffff8121435e)
Location: include/linux/audit.h:146
Inline: True
```
```
In fs/pipe.c (ffffffff81215db8)
Location: include/linux/audit.h:146
Inline: True
```
```
In fs/namei.c (ffffffff812181b6)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - fs/namei.c:may_delete
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:getname_kernel
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_mountpoint
```
```
In fs/xattr.c (ffffffff81232ee8)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fremovexattr
```
```
In fs/devpts/inode.c (ffffffff8128e537)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8131dc29)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8131f37d)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81324ccf)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcctl_pre_down_nolock
```
```
In ipc/shm.c (ffffffff8132b116)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff8132c2cc)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_notify
```
```
In security/commoncap.c (ffffffff8133afd3)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff816fcc16)
Location: include/linux/audit.h:146
Inline: True
Inline callers:
  - net/socket.c:move_addr_to_user
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
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
In kernel/capability.c (ffffffff8108d62a)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
```
```
In kernel/ptrace.c (ffffffff8108dde9)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff8109029f)
Location: include/linux/audit.h:249
Inline: True
```
```
In kernel/auditsc.c (ffffffff811317b5)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_signal_info
```
```
In kernel/audit_watch.c (ffffffff8113212e)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/seccomp.c (ffffffff81143c7a)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In mm/mmap.c (ffffffff811e1926)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In fs/open.c (ffffffff8123105c)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
```
```
In fs/exec.c (ffffffff8123b0f0)
Location: include/linux/audit.h:249
Inline: True
```
```
In fs/pipe.c (ffffffff8123cc16)
Location: include/linux/audit.h:249
Inline: True
```
```
In fs/namei.c (ffffffff812416ab)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff8125b834)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/devpts/inode.c (ffffffff812bbac9)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813526c9)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8135483d)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81359e77)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/shm.c (ffffffff8135fdb6)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff81360f64)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
```
```
In security/commoncap.c (ffffffff81370605)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff81766620)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:move_addr_to_user
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
In kernel/capability.c (ffffffff8109256a)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
```
```
In kernel/ptrace.c (ffffffff81093539)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/signal.c (ffffffff8109521f)
Location: include/linux/audit.h:249
Inline: True
```
```
In kernel/auditsc.c (ffffffff8113b535)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_signal_info
```
```
In kernel/audit_watch.c (ffffffff8113be8e)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/seccomp.c (ffffffff8114db4a)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In mm/mmap.c (ffffffff811f1916)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In fs/open.c (ffffffff8124360c)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
```
```
In fs/exec.c (ffffffff8124decc)
Location: include/linux/audit.h:249
Inline: True
```
```
In fs/pipe.c (ffffffff8124f976)
Location: include/linux/audit.h:249
Inline: True
```
```
In fs/namei.c (ffffffff81254552)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff8126ede4)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/devpts/inode.c (ffffffff812d1111)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8136897c)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8136aafd)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81370357)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/shm.c (ffffffff813765b6)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff81377774)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/mqueue.c:SyS_mq_notify
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
```
```
In security/commoncap.c (ffffffff81386e15)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff817936a0)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:move_addr_to_user
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
In kernel/capability.c (ffffffff8108f6ef)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
```
```
In kernel/ptrace.c (ffffffff81090648)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module.c (ffffffff81118c95)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:SyS_delete_module
```
```
In kernel/auditsc.c (ffffffff8113ca2f)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info
```
```
In kernel/audit_watch.c (ffffffff8113d4ba)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/seccomp.c (ffffffff81150a59)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In mm/mmap.c (ffffffff811fc61c)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In fs/open.c (ffffffff8124ed50)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
```
```
In fs/exec.c (ffffffff81259f1e)
Location: include/linux/audit.h:248
Inline: True
```
```
In fs/pipe.c (ffffffff8125b8c4)
Location: include/linux/audit.h:248
Inline: True
```
```
In fs/namei.c (ffffffff812601ea)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff8127c5f4)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/devpts/inode.c (ffffffff812e2780)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8137cf0b)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8137f14d)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81383727)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/shm.c (ffffffff8138a12c)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In ipc/mqueue.c (ffffffff8138b296)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff8139ba66)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff817b1ae6)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff817fb1cc)
Location: include/linux/audit.h:248
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
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
In kernel/capability.c (ffffffff810965af)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - kernel/capability.c:SyS_capset
```
```
In kernel/ptrace.c (ffffffff810974b8)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module.c (ffffffff81124241)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:SyS_delete_module
```
```
In kernel/auditsc.c (ffffffff811497af)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info
```
```
In kernel/audit_watch.c (ffffffff8114a288)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/seccomp.c (ffffffff8115d24f)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In mm/mmap.c (ffffffff81214b5c)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In fs/open.c (ffffffff81270cd0)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - fs/open.c:SyS_fchown
  - fs/open.c:SyS_fchmod
```
```
In fs/exec.c (ffffffff8127c1c6)
Location: include/linux/audit.h:240
Inline: True
```
```
In fs/pipe.c (ffffffff8127dc94)
Location: include/linux/audit.h:240
Inline: True
```
```
In fs/namei.c (ffffffff812828ca)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff8129f094)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:SyS_flistxattr
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:SyS_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812bf2f0)
Location: include/linux/audit.h:240
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813071b0)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813a1e1b)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813a418d)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff813a7b97)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/shm.c (ffffffff813ae360)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In ipc/mqueue.c (ffffffff813b0626)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff813c1075)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff81829c86)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_socketcall
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff81878b4c)
Location: include/linux/audit.h:240
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
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
In kernel/capability.c (ffffffff81099603)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff8109a99b)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module.c (ffffffff811326e2)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff811523cf)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff811580c7)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info
```
```
In kernel/audit_watch.c (ffffffff81158cdb)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff81235988)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8129693b)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812a2f7e)
Location: include/linux/audit.h:250
Inline: True
```
```
In fs/pipe.c (ffffffff812a4c34)
Location: include/linux/audit.h:250
Inline: True
```
```
In fs/namei.c (ffffffff812ab73f)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff812c53e9)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812e824e)
Location: include/linux/audit.h:250
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81335145)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813d114b)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813d356f)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff813d6f84)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff813d7e2d)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff813dab7a)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff813de8cc)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff813e12f5)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff813f1fdd)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff81873f62)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff818ca01e)
Location: include/linux/audit.h:250
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810a1987)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810a2bcb)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module.c (ffffffff8113dff4)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8115f07f)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff811650c9)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info
```
```
In kernel/audit_watch.c (ffffffff81165c7b)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff81249188)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812ab72b)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812b7fb8)
Location: include/linux/audit.h:249
Inline: True
```
```
In fs/pipe.c (ffffffff812b9d04)
Location: include/linux/audit.h:249
Inline: True
```
```
In fs/namei.c (ffffffff812be34f)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff812da5e9)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fcf27)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff8134c3d5)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813ebc10)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813edc5f)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff813f1594)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff813f2437)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff813f51c4)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff813f8fcc)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff813fbed5)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff8140d2ad)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff818946d2)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff818f503c)
Location: include/linux/audit.h:249
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810a63cf)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810a787e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8112f490)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff811499bd)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8116b413)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff81171bad)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff81172800)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff8125b47b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812c7f2b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812d44bf)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/pipe.c (ffffffff812d6984)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (ffffffff812db04a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff812f8bb9)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131dc60)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff81374d9f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81417cfe)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81419eef)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff8141d846)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8141ed2f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142153a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81425542)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff814281a5)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff8143a438)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff818dea92)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff81953ede)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810ac9af)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810ade9e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8113b450)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81155628)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff811772f3)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff8117da5d)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff8117e6b0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff81269b5b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812d993b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812e604f)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/pipe.c (ffffffff812e84f4)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (ffffffff812ecb5a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff8130a7e9)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81330aa0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff8138d01f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81431bbe)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81433d3f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81437696)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81438b7f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8143b32a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8143f292)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81441ed5)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff814542a8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff81910c62)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8198a42e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810b469f)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810b597e)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8114a49e)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81166b09)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/audit.c (ffffffff8118a033)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
```
```
In kernel/auditsc.c (ffffffff81190d1d)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff81191b3f)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff8129a38b)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8130f6fb)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff8131cc80)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff8131eb86)
Location: include/linux/audit.h:309
Inline: True
```
```
In fs/namei.c (ffffffff8132683f)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff813437e9)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136a8bf)
Location: include/linux/audit.h:309
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813d846f)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814814aa)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81483a6b)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff814876e7)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81488635)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8148b88a)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8148fe02)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81492ab5)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff814a6cac)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In net/socket.c (ffffffff819e2e8a)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff81a627be)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810af88d)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810b0b6e)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff811469ee)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff8116329d)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/audit.c (ffffffff81187343)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
```
```
In kernel/auditsc.c (ffffffff8118df45)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff8118ecef)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff812a55a3)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8131b9ab)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff81327e15)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff8132a0d6)
Location: include/linux/audit.h:326
Inline: True
```
```
In fs/namei.c (ffffffff81331cb0)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff8134ffa9)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813780af)
Location: include/linux/audit.h:326
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813ea10e)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8149ef73)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a10df)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff814a4d07)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff814a5c65)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814a8ea9)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814ad512)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff814b03b5)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff814c4259)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In net/socket.c (ffffffff819e2b0a)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff81a6a8de)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810b0e2b)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810b210e)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff81147b5e)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81163eb7)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/audit.c (ffffffff81188273)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
```
```
In kernel/auditsc.c (ffffffff8118eeb5)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff8118fb1b)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff812aad3a)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff81321afb)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff8132dd45)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff81330086)
Location: include/linux/audit.h:326
Inline: True
```
```
In fs/namei.c (ffffffff81335d7b)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff81356a58)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137ec5f)
Location: include/linux/audit.h:326
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813f0c4e)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814a4f53)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a720f)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff814aacc7)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff814abc35)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814b0299)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814b3392)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff814b6205)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff814ca608)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In net/socket.c (ffffffff819c8b2a)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff81a5300e)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810c2e32)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810c3f1a)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8116b67e)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81189593)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/audit.c (ffffffff811b0793)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
```
```
In kernel/auditsc.c (ffffffff811b7ccd)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff811b89fb)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff812ec3d5)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8136efdb)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff8137b525)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff8137d846)
Location: include/linux/audit.h:326
Inline: True
```
```
In fs/namei.c (ffffffff8138385b)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff813a5438)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cbd3c)
Location: include/linux/audit.h:326
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81442b3e)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814fd07c)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff2bf)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81503166)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff815040f7)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8150835b)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8150ba02)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8150eb45)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff81523499)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In net/socket.c (ffffffff81a77e90)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff81b0bce9)
Location: include/linux/audit.h:326
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810da28a)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810db530)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module/main.c (ffffffff8118f352)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/timekeeping.c (ffffffff8119f66c)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/audit.c (ffffffff811e2953)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
```
```
In kernel/auditsc.c (ffffffff811eab85)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff811eb932)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff8134f2c2)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff813edeba)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - fs/open.c:__do_sys_openat2
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff813fa5e2)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff813fd865)
Location: include/linux/audit.h:337
Inline: True
```
```
In fs/namei.c (ffffffff81404804)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff81428a80)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81452f5d)
Location: include/linux/audit.h:337
Inline: True
```
```
In fs/devpts/inode.c (ffffffff814be8da)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8158d367)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81590589)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff815947b7)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff815959e3)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff815978aa)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8159d03c)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8159ff42)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff815b70d2)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In net/socket.c (ffffffff81beb3cf)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/compat.c (ffffffff81c92452)
Location: include/linux/audit.h:337
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810fa26a)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810fb5f0)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module/main.c (ffffffff811cc25e)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/timekeeping.c (ffffffff811de36c)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/audit.c (ffffffff81228823)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
```
```
In kernel/auditsc.c (ffffffff81230e85)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff81231d32)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff813c88b5)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8147664a)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - fs/open.c:__do_sys_openat2
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff81484112)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff81487465)
Location: include/linux/audit.h:334
Inline: True
```
```
In fs/namei.c (ffffffff8148ec84)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff814b60e0)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e1ce6)
Location: include/linux/audit.h:334
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8155677a)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81633e67)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637a09)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff8163d437)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8163e243)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff81640a62)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8164652c)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81649812)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff8166246e)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In net/socket.c (ffffffff81d97d5f)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/compat.c (ffffffff81e4dac2)
Location: include/linux/audit.h:334
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff81106400)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff81107690)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module/main.c (ffffffff811df57d)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/timekeeping.c (ffffffff811f283c)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/audit.c (ffffffff8123ee23)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
```
```
In kernel/auditsc.c (ffffffff81247a25)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff812489c2)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff813fcab5)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff814aaef5)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff814b8a25)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff814bc265)
Location: include/linux/audit.h:333
Inline: True
```
```
In fs/namei.c (ffffffff814c3e16)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:__filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff814ea910)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815185f4)
Location: include/linux/audit.h:333
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8158e53a)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8166c193)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166fe09)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81675953)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81676733)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff81678fbf)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8167ea3c)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81681d78)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff8169a8b4)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In net/socket.c (ffffffff81e063cf)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/compat.c (ffffffff81ea9112)
Location: include/linux/audit.h:333
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff8110fd50)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff81110ff0)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module/main.c (ffffffff811f52ad)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/timekeeping.c (ffffffff8120897c)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/audit.c (ffffffff81258ca3)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_path_denied
```
```
In kernel/auditsc.c (ffffffff81261835)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff812628a1)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff81429485)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff814dc395)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff814eaf35)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff814ee795)
Location: include/linux/audit.h:332
Inline: True
```
```
In fs/namei.c (ffffffff814f644a)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:__ia32_sys_unlink
  - fs/namei.c:__x64_sys_unlink
  - fs/namei.c:__ia32_sys_rmdir
  - fs/namei.c:__x64_sys_rmdir
  - fs/namei.c:__ia32_sys_mkdir
  - fs/namei.c:__x64_sys_mkdir
  - fs/namei.c:__x64_sys_mkdirat
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:__x64_sys_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:__filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff8151e7b0)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154c9d4)
Location: include/linux/audit.h:332
Inline: True
```
```
In fs/devpts/inode.c (ffffffff815c7250)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff816a6633)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff816aaa1f)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/tracefs/event_inode.c (ffffffff816abf1f)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
```
```
In ipc/util.c (ffffffff816b1d13)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff816b2af3)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff816b53af)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff816bae2c)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff816be183)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff816d6ff4)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In net/socket.c (ffffffff81ec2c8f)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/compat.c (ffffffff81f6bbd2)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffff8000101065cc)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__arm64_sys_capset
```
```
In kernel/ptrace.c (ffff800010107fa4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffff8000101a5644)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffff8000101c49f4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__arm64_sys_delete_module
```
```
In kernel/audit.c (ffff8000101ec2ac)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffff8000101f28fc)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffff8000101f3500)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffff800010300fd8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffff80001037ec88)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffff80001038e1c8)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/pipe.c (ffff8000103913bc)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (ffff80001039623c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffff8000103be264)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:__arm64_sys_flistxattr
  - fs/xattr.c:__arm64_sys_fgetxattr
  - fs/xattr.c:__arm64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103edc54)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffff80001045ed08)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffff80001051691c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffff800010519800)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffff80001051decc)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffff80001051f6dc)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffff800010522ef4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffff8000105276a0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffff80001052a910)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffff80001053f3b0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffff800010ba75d4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffff800010c32fc8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (c0361380)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
```
```
In kernel/ptrace.c (c0362504)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/time/timekeeping.c (c03f06a0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (c040bdc0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/audit.c (c042bec0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (c0432e00)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (c0433a08)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (c051fa34)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (c05695b4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (c0575cdc)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/pipe.c (c0577de8)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (c057b698)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (c059c2b8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (c05c450c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (c061f754)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c06d16d4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c06d3f0c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (c06da334)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (c06dbe98)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:ksys_msgctl
```
```
In ipc/sem.c (c06de4d4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:ksys_semctl
```
```
In ipc/shm.c (c06e0e68)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e4f1c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
```
```
In security/commoncap.c (c06f53c4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (c0cc6060)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
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
In kernel/capability.c (c00000000014d944)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
```
```
In kernel/ptrace.c (c00000000014f374)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (c0000000002074a8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (c00000000022be68)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/audit.c (c00000000025dc28)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (c000000000267140)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (c000000000268090)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (c0000000003cd310)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (c0000000004749d0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (c000000000486740)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/pipe.c (c0000000004894d8)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (c00000000048e490)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (c0000000004bcdd8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f5570)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (c00000000057ae94)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c00000000065f8e8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c000000000662e70)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (c000000000667360)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (c000000000669130)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (c00000000066cb30)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (c000000000672084)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (c0000000006755ac)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (c00000000068fe30)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (c000000000c7d770)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (c000000000d2bf2c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffe0000cb3f0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
```
```
In kernel/ptrace.c (ffffffe0000cc3c8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/time/timekeeping.c (ffffffe000131a8c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffe000145334)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/audit.c (ffffffe0001609d4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffe000165f48)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffe0001669ee)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffe00020e4f2)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffe0002548e2)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffe00025ee02)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/pipe.c (ffffffe000260a60)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (ffffffe000264726)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffe00027fdfc)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a15d4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffe0002ee87a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffe000380022)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffe000382b1c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffe000385688)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffe000386886)
Location: include/linux/audit.h:292
Inline: True
```
```
In ipc/sem.c (ffffffe000389e96)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:__se_sys_semctl
```
```
In ipc/shm.c (ffffffe00038b600)
Location: include/linux/audit.h:292
Inline: True
```
```
In ipc/mqueue.c (ffffffe00038cec4)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
```
```
In security/commoncap.c (ffffffe00039c92c)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffe00073afd2)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
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
In kernel/capability.c (ffffffff810a6d1f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810a820e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff81133c00)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff8114dc48)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8116f913)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff8117607d)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff81176cd0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff812621ab)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812d1f1b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812de62f)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/pipe.c (ffffffff812e0ad4)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (ffffffff812e513a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff81302dc9)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81329080)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff813855ff)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142a19e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8142c31f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff8142fc76)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8143115f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8143390a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81437872)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8143a4b5)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff8144c888)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff818b0c62)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8192a29e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810956ff)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff81096bce)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff81126660)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81140ef8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff81162ab3)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff8116921d)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff81169e70)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff812545cb)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812c2b9b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812cf95f)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/pipe.c (ffffffff812d1714)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (ffffffff812d5d7a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff812f39e9)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81319c20)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff8137608f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8141ac1e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8141cd9f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff814206f6)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81421bdf)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142438a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814282e2)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8142af25)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff8143d2d8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff8186abb2)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff818e404e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810a627f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810a776e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff81131920)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff8114baf8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8116d6e3)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff81173e4d)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff81174aa0)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff8125ff4b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812cfd2b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812dc43f)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/pipe.c (ffffffff812de8e4)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (ffffffff812e2f4a)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff81300bb9)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81326b50)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff813830cf)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142633e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814284bf)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff8142be16)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8142d2ff)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142faaa)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81433a12)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81436655)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff81448928)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff81901c62)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8197b42e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
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
In kernel/capability.c (ffffffff810ae35f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810af88e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8113e340)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff811587e8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8117aed3)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff8118172b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_signal_info_syscall
```
```
In kernel/audit_watch.c (ffffffff81182380)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff8126f91b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812e0b3b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812ed1d6)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/pipe.c (ffffffff812ef854)
Location: include/linux/audit.h:292
Inline: True
```
```
In fs/namei.c (ffffffff812f2e88)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:getname_kernel
```
```
In fs/xattr.c (ffffffff81311ef9)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:__ia32_sys_flistxattr
  - fs/xattr.c:__x64_sys_flistxattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8133896b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff81396bef)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8143d1fe)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8143f37f)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81442e36)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8144365b)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814453e9)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8144a16d)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8144cdf9)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_getsetattr
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
```
In security/commoncap.c (ffffffff8145fcf8)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In net/socket.c (ffffffff81922c02)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8199d97e)
Location: include/linux/audit.h:292
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
</details>
</li>
</ul>

## Differences
