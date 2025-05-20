# Function: <code>audit_context</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003e35)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff81099603)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff8109a99b)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module.c (ffffffff811326e2)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff811523cf)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff811586e5)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/audit_watch.c (ffffffff81158cdb)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff81235988)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8129693b)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812a2f7e)
Location: include/linux/audit.h:245
Inline: True
```
```
In fs/pipe.c (ffffffff812a4c34)
Location: include/linux/audit.h:245
Inline: True
```
```
In fs/namei.c (ffffffff812ab73f)
Location: include/linux/audit.h:245
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
Location: include/linux/audit.h:245
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
Location: include/linux/audit.h:245
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81335145)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813d114b)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813d356f)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff813d6f84)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff813d7e2d)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff813dab7a)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff813de8cc)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff813e12f5)
Location: include/linux/audit.h:245
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
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffff813fc652)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff81404aaf)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81413bad)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff814214bc)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff8145013a)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff81453a3b)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In net/socket.c (ffffffff81873f62)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff818991bd)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff818ca01e)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194ae32)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819527e6)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff819b7440)
Location: include/linux/audit.h:245
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/x86/entry/common.c (ffffffff81003935)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff810a1987)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810a2bcb)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/module.c (ffffffff8113dff4)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8115f07f)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
```
```
In kernel/auditsc.c (ffffffff811656d5)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:audit_signal_info
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81165c7b)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In mm/mmap.c (ffffffff81249188)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812ab72b)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812b7fb8)
Location: include/linux/audit.h:244
Inline: True
```
```
In fs/pipe.c (ffffffff812b9d04)
Location: include/linux/audit.h:244
Inline: True
```
```
In fs/namei.c (ffffffff812be34f)
Location: include/linux/audit.h:244
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
Location: include/linux/audit.h:244
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
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff8134c3d5)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813ebc10)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813edc5f)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff813f1594)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff813f2437)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff813f51c4)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff813f8fcc)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff813fbed5)
Location: include/linux/audit.h:244
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
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffff81418da1)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff81420b0f)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814300f4)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff8143db3c)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff8146d11a)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff81470c16)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff81470ea5)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In net/socket.c (ffffffff818946d2)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff818bb65f)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff818f503c)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d8d2)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81984d86)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff819ee700)
Location: include/linux/audit.h:244
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/x86/entry/common.c (ffffffff810041c5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff810a63cf)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810a787e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8112f490)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff811499bd)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8116b54e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8116ba05)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (ffffffff81172235)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81172800)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8117312e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff81173e16)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:trim_marked
```
```
In mm/mmap.c (ffffffff8125b47b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812c7f2b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812d44bf)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/pipe.c (ffffffff812d6984)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (ffffffff812db04a)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff81374d9f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81417cfe)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81419eef)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff8141d846)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8141ed2f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142153a)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81425542)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff814281a5)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffff81446b26)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff8144e6f1)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8145da77)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff8146b6fc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff8149a82b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e5f7)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff8149e8ff)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a2b25)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff8166dee5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff818dea92)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff8190757e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81953ede)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e6cfc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819eefc6)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81a5d940)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/x86/entry/common.c (ffffffff810041c5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff810ac9af)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810ade9e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8113b450)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81155628)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8117742e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff811778e5)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (ffffffff8117e0e5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff8117e6b0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8117ef9e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff8117fc86)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:trim_marked
```
```
In mm/mmap.c (ffffffff81269b5b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812d993b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812e604f)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/pipe.c (ffffffff812e84f4)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (ffffffff812ecb5a)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff8138d01f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81431bbe)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81433d3f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81437696)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81438b7f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8143b32a)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8143f292)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81441ed5)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffff814606be)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff81468519)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81477827)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff814854dc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff814b4a2b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff814b8aa7)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b8d9f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814bd7f5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff81690555)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff81910c62)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff81939b65)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff8198a42e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1dddc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25e96)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81a94570)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/x86/entry/common.c (ffffffff8100525a)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff810b469f)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810b597e)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8114a49e)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81166b09)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/audit.c (ffffffff81189ef0)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8118a495)
Location: include/linux/audit.h:304
Inline: True
```
```
In kernel/auditsc.c (ffffffff811914d5)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:handle_path
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_proctitle
```
```
In kernel/audit_watch.c (ffffffff81191c4f)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8119242f)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_autoremove_mark_rule
```
```
In kernel/audit_tree.c (ffffffff81192db4)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:trim_marked
```
```
In kernel/bpf/syscall.c (ffffffff81200426)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In mm/mmap.c (ffffffff8129a38b)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8130f6fb)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff8131cc80)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff8131eb86)
Location: include/linux/audit.h:304
Inline: True
```
```
In fs/namei.c (ffffffff8132683f)
Location: include/linux/audit.h:304
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
Location: include/linux/audit.h:304
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
Location: include/linux/audit.h:304
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813d846f)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814814aa)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81483a6b)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff814876e7)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81488635)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8148b88a)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8148fe02)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81492ab5)
Location: include/linux/audit.h:304
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
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/selinux/hooks.c (ffffffff814b0c46)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff814bc369)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814ccc80)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validtrans_handle_fail
```
```
In security/lsm_audit.c (ffffffff814db68c)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff81513f7b)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff81518713)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff81518f59)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8151e0e5)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff81742c95)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff819e2e8a)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff81a0f105)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81a627be)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0fd1c)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b181eb)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81b8fb53)
Location: include/linux/audit.h:304
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810b0b6e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/entry/common.c (ffffffff8113b82d)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timekeeping.c (ffffffff811469ee)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff8116329d)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/audit.c (ffffffff811871f0)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff81187705)
Location: include/linux/audit.h:321
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118e6f5)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:handle_path
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
  - kernel/auditsc.c:audit_log_proctitle
```
```
In kernel/audit_watch.c (ffffffff8118edff)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8118f5bf)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_autoremove_mark_rule
```
```
In kernel/audit_tree.c (ffffffff8118ff24)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:trim_marked
```
```
In kernel/bpf/syscall.c (ffffffff811ff87c)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In mm/mmap.c (ffffffff812a55a3)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8131b9ab)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff81327e15)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff8132a0d6)
Location: include/linux/audit.h:321
Inline: True
```
```
In fs/namei.c (ffffffff81331cb0)
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813ea10e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8149ef73)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a10df)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff814a4d07)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff814a5c65)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814a8ea9)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814ad512)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff814b03b5)
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/selinux/hooks.c (ffffffff814cde56)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff814d9e4e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814ea44d)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
  - security/selinux/ss/services.c:security_validtrans_handle_fail
```
```
In security/lsm_audit.c (ffffffff814f8b1c)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff815310db)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In security/integrity/ima/ima_api.c (ffffffff815356e3)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff81535ff9)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8153aeb5)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff8175eb3e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff819e2b0a)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff81c31450)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81a6a8de)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1cc3c)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2695b)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81b9f793)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810b210e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/entry/common.c (ffffffff8113cb0d)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timekeeping.c (ffffffff81147b5e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81163eb7)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/audit.c (ffffffff811883e3)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff81188775)
Location: include/linux/audit.h:321
Inline: True
```
```
In kernel/auditsc.c (ffffffff8118f675)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
```
```
In kernel/audit_watch.c (ffffffff8118fc2f)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81190571)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff81190e54)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:trim_marked
```
```
In kernel/bpf/syscall.c (ffffffff81200227)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In mm/mmap.c (ffffffff812aad3a)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff81321afb)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff8132dd45)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff81330086)
Location: include/linux/audit.h:321
Inline: True
```
```
In fs/namei.c (ffffffff81335d7b)
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
Inline: True
```
```
In fs/devpts/inode.c (ffffffff813f0c4e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814a4f53)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a720f)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff814aacc7)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff814abc35)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814b0299)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814b3392)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff814b6205)
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/selinux/hooks.c (ffffffff814d45a6)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff814e12fc)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff814f10b7)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff814ff8ac)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff8153950b)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In security/integrity/ima/ima_api.c (ffffffff8153dd09)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153e71f)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81543585)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff8174297e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff819c8b2a)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff81c23735)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81a5300e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a9bc)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1458b)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81b8e863)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810c3f1a)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/entry/common.c (ffffffff8115fc2d)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/time/timekeeping.c (ffffffff8116b67e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81189593)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
```
In kernel/audit.c (ffffffff811b0903)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff811b0cd5)
Location: include/linux/audit.h:321
Inline: True
```
```
In kernel/auditsc.c (ffffffff811b8555)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_lsm
```
```
In kernel/audit_watch.c (ffffffff811b8b0f)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811b9451)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff811b9d34)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/audit_tree.c:evict_chunk
  - kernel/audit_tree.c:trim_marked
```
```
In kernel/bpf/syscall.c (ffffffff81231f3d)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In mm/mmap.c (ffffffff812ec3d5)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8136efdb)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff8137b525)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff8137d846)
Location: include/linux/audit.h:321
Inline: True
```
```
In fs/namei.c (ffffffff8138385b)
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
Inline: True
```
```
In fs/devpts/inode.c (ffffffff81442b3e)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814fd07c)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff2bf)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81503166)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff815040f7)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8150835b)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8150ba02)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8150eb45)
Location: include/linux/audit.h:321
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
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/selinux/hooks.c (ffffffff8152d266)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff8153a27c)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8154b6d7)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff8155a91c)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff81597d2d)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In security/integrity/ima/ima_api.c (ffffffff8159cbc6)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159db0f)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff815a3cb6)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff817c33ce)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff81a77e90)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff81d365d2)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81b0bce9)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bce19c)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd868b)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81c5adf3)
Location: include/linux/audit.h:321
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810db530)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/entry/common.c (ffffffff8118a13d)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff8118f352)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/timekeeping.c (ffffffff8119f66c)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/audit.c (ffffffff811e2b12)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff811e3055)
Location: include/linux/audit.h:332
Inline: True
```
```
In kernel/auditsc.c (ffffffff811eb435)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_openat2_how
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff811eba61)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811ec4db)
Location: include/linux/audit.h:332
Inline: True
```
```
In kernel/audit_tree.c (ffffffff811ecf44)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:trim_marked
```
```
In kernel/bpf/syscall.c (ffffffff81275238)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In mm/mmap.c (ffffffff8134f2c2)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff813edeba)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/open.c:__do_sys_openat2
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff813fa5e2)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff813fd865)
Location: include/linux/audit.h:332
Inline: True
```
```
In fs/namei.c (ffffffff81404804)
Location: include/linux/audit.h:332
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
In fs/notify/fanotify/fanotify.c (ffffffff81452f5d)
Location: include/linux/audit.h:332
Inline: True
```
```
In fs/devpts/inode.c (ffffffff814be8da)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8158d367)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81590589)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff815947b7)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff815959e3)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff815978aa)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8159d03c)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8159ff42)
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
In security/commoncap.c (ffffffff815b70d2)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/selinux/hooks.c (ffffffff815c5ea6)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff815d1c3b)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff815e44d8)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff815f56d0)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff8163c51a)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In security/integrity/ima/ima_api.c (ffffffff81641d54)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff8164301f)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8164a6c4)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In io_uring/io_uring.c (ffffffff816cdbdf)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
```
```
In drivers/tty/tty_audit.c (ffffffff818fff8f)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/md/dm-audit.c (ffffffff81b6f7e7)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
```
```
In net/socket.c (ffffffff81beb3cf)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/core/dev.c (ffffffff81f02d97)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81c92452)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d633dc)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6ecb4)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81dfc8ed)
Location: include/linux/audit.h:332
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff810fb5f0)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/entry/common.c (ffffffff811c667d)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff811cc25e)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/timekeeping.c (ffffffff811de36c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/audit.c (ffffffff812289f2)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff81229455)
Location: include/linux/audit.h:329
Inline: True
```
```
In kernel/auditsc.c (ffffffff812317f5)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_openat2_how
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81231e71)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8123298b)
Location: include/linux/audit.h:329
Inline: True
```
```
In kernel/audit_tree.c (ffffffff812334d4)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:trim_marked
```
```
In kernel/bpf/syscall.c (ffffffff812c58de)
Location: include/linux/audit.h:329
Inline: True
```
```
In mm/mmap.c (ffffffff813c88b5)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff8147664a)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/open.c:__do_sys_openat2
  - fs/open.c:ksys_fchown
  - fs/open.c:__ia32_sys_fchmod
  - fs/open.c:__x64_sys_fchmod
```
```
In fs/exec.c (ffffffff81484112)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff81487465)
Location: include/linux/audit.h:329
Inline: True
```
```
In fs/namei.c (ffffffff8148ec84)
Location: include/linux/audit.h:329
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
Location: include/linux/audit.h:329
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
Location: include/linux/audit.h:329
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8155677a)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81633e67)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637a09)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff8163d437)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8163e243)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff81640a62)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8164652c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81649812)
Location: include/linux/audit.h:329
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
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/selinux/hooks.c (ffffffff81672ca4)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff8167fa6b)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81693848)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff816a61c0)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff816f3d6a)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In security/integrity/ima/ima_api.c (ffffffff816f9dc4)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb2df)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff81703814)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In io_uring/io_uring.c (ffffffff81790c1c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
```
```
In drivers/tty/tty_audit.c (ffffffff81a599ff)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/md/dm-audit.c (ffffffff81d0bdd7)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
```
```
In net/socket.c (ffffffff81d97d5f)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/core/dev.c (ffffffff81dce383)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81e4dac2)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2e07c)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a3c4)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81fd12ed)
Location: include/linux/audit.h:329
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff81107690)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/entry/common.c (ffffffff811d929d)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
```
```
In kernel/module/main.c (ffffffff811df57d)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/timekeeping.c (ffffffff811f283c)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/audit.c (ffffffff8123eff2)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8123fa55)
Location: include/linux/audit.h:328
Inline: True
```
```
In kernel/auditsc.c (ffffffff81248485)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_openat2_how
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81248b01)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8124960b)
Location: include/linux/audit.h:328
Inline: True
```
```
In kernel/audit_tree.c (ffffffff8124a176)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:trim_marked
```
```
In kernel/bpf/syscall.c (ffffffff812ec8be)
Location: include/linux/audit.h:328
Inline: True
```
```
In mm/mmap.c (ffffffff813fcab5)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff814aaef5)
Location: include/linux/audit.h:328
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
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff814bc265)
Location: include/linux/audit.h:328
Inline: True
```
```
In fs/namei.c (ffffffff814c3e16)
Location: include/linux/audit.h:328
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
Location: include/linux/audit.h:328
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
Location: include/linux/audit.h:328
Inline: True
```
```
In fs/devpts/inode.c (ffffffff8158e53a)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8166c193)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166fe09)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81675953)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81676733)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff81678fbf)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8167ea3c)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81681d78)
Location: include/linux/audit.h:328
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
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/selinux/hooks.c (ffffffff816ab186)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff816b7b5e)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff816cbd4a)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff816deba0)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff8172de9a)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In security/integrity/ima/ima_api.c (ffffffff81733ef8)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff8173539f)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8173d844)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In io_uring/io_uring.c (ffffffff817d211d)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
```
```
In drivers/tty/tty_audit.c (ffffffff81aa403f)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/md/dm-audit.c (ffffffff81d74f07)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
```
```
In net/socket.c (ffffffff81e063cf)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/core/dev.c (ffffffff81e3ef81)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81ea9112)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f82c)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f99de4)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff8204ceff)
Location: include/linux/audit.h:328
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/capability.c:__do_sys_capset
```
```
In kernel/ptrace.c (ffffffff81110ff0)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/entry/common.c (ffffffff811eebdd)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
  - kernel/entry/common.c:syscall_trace_enter
```
```
In kernel/module/main.c (ffffffff811f52ad)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
```
```
In kernel/time/timekeeping.c (ffffffff8120897c)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/audit.c (ffffffff81258e5a)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_path_denied
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff812598a5)
Location: include/linux/audit.h:327
Inline: True
```
```
In kernel/auditsc.c (ffffffff812622e5)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:__audit_log_nfcfg
  - kernel/auditsc.c:__audit_ntp_log
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_openat2_how
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_uring_exit
  - kernel/auditsc.c:__audit_uring_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_proctitle
```
```
In kernel/audit_watch.c (ffffffff812629e1)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff812634fb)
Location: include/linux/audit.h:327
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81264086)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:trim_marked
```
```
In kernel/bpf/syscall.c (ffffffff8130afce)
Location: include/linux/audit.h:327
Inline: True
```
```
In mm/mmap.c (ffffffff81429485)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff814dc395)
Location: include/linux/audit.h:327
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
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
```
```
In fs/pipe.c (ffffffff814ee795)
Location: include/linux/audit.h:327
Inline: True
```
```
In fs/namei.c (ffffffff814f644a)
Location: include/linux/audit.h:327
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
Location: include/linux/audit.h:327
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
Location: include/linux/audit.h:327
Inline: True
```
```
In fs/devpts/inode.c (ffffffff815c7250)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff816a6633)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff816aaa1f)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/tracefs/event_inode.c (ffffffff816abf1f)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
```
```
In ipc/util.c (ffffffff816b1d13)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff816b2af3)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff816b53af)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff816bae2c)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff816be183)
Location: include/linux/audit.h:327
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
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/selinux/hooks.c (ffffffff816e8183)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff816f3441)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81708a0a)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff8171b770)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff8176e7fa)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In security/integrity/ima/ima_api.c (ffffffff817749e8)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff81775e7f)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8177e674)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In io_uring/io_uring.c (ffffffff81815430)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
```
```
In drivers/tty/tty_audit.c (ffffffff81af69ff)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/md/dm-audit.c (ffffffff81e2c017)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - drivers/md/dm-audit.c:dm_audit_log_bio
  - drivers/md/dm-audit.c:dm_audit_log_ti
  - drivers/md/dm-audit.c:dm_audit_log_ti
```
```
In net/socket.c (ffffffff81ec2c8f)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/core/dev.c (ffffffff81efd8de)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff81f6bbd2)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205b9bc)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff82067144)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff8211f39f)
Location: include/linux/audit.h:327
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/arm64/kernel/ptrace.c (ffff80001008ee88)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
```
```
In kernel/capability.c (ffff8000101065cc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__arm64_sys_capset
```
```
In kernel/ptrace.c (ffff800010107fa4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffff8000101a5644)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffff8000101c49f4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__arm64_sys_delete_module
```
```
In kernel/audit.c (ffff8000101ec398)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffff8000101eca74)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (ffff8000101f2f60)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffff8000101f3500)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffff8000101f3ef0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffff8000101f4bb4)
Location: include/linux/audit.h:287
Inline: True
```
```
In mm/mmap.c (ffff800010300fd8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffff80001037ec88)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffff80001038e1c8)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/pipe.c (ffff8000103913bc)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (ffff80001039623c)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:__arm64_sys_flistxattr
  - fs/xattr.c:__arm64_sys_fgetxattr
  - fs/xattr.c:__arm64_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103edc54)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffff80001045ed08)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffff80001051691c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffff800010519800)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffff80001051decc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffff80001051f6dc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffff800010522ef4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffff8000105276a0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffff80001052a910)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffff80001054de08)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffff800010556bbc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffff800010567574)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffff800010577a20)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffff8000105acb7c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0da0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffff8000105b116c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffff8000105b66e8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffff8000108632b0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffff800010ba75d4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffff800010bd58b4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffff800010c32fc8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd963c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3484)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffff800010d62d2c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/arm/kernel/ptrace.c (c030d060)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
```
```
In kernel/capability.c (c0361380)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
```
```
In kernel/ptrace.c (c0362504)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/time/timekeeping.c (c03f06a0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (c040bdc0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/audit.c (c042c048)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (c042c80c)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (c04334d8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (c0433a08)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (c0434300)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (c0434b0c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In mm/mmap.c (c051fa34)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (c05695b4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (c0575cdc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/pipe.c (c0577de8)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (c057b698)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (c05c450c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (c061f754)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c06d16d4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c06d3f0c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (c06da334)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (c06dbe98)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:ksys_msgctl
```
```
In ipc/sem.c (c06de4d4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:ksys_semctl
```
```
In ipc/shm.c (c06e0e68)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e4f1c)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (c0706a78)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (c070b9c4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (c071ba88)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (c072a85c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (c075c3fc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (c0760474)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (c07607ac)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (c07656bc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (c0968fb4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (c0cc6060)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/core/dev.c (c0cf052c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (c0de47c8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (c0deca64)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (c0e61c7c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/powerpc/kernel/ptrace.c (c000000000019500)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
```
```
In kernel/capability.c (c00000000014d944)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
```
```
In kernel/ptrace.c (c00000000014f374)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (c0000000002074a8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (c00000000022be68)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/audit.c (c00000000025de10)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (c00000000025e980)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (c000000000267968)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (c000000000268090)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (c000000000268f60)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (c0000000002699b0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
```
```
In mm/mmap.c (c0000000003cd310)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (c0000000004749d0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (c000000000486740)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/pipe.c (c0000000004894d8)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (c00000000048e490)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f5570)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (c00000000057ae94)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c00000000065f8e8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c000000000662e70)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (c000000000667360)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (c000000000669130)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (c00000000066cb30)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (c000000000672084)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (c0000000006755ac)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (c0000000006ac95c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (c0000000006b40ac)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (c0000000006ca98c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (c0000000006e1130)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (c00000000072afc4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (c000000000730bec)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (c000000000731130)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (c00000000073a7b8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (c000000000902064)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (c000000000c7d770)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (c000000000cb4eb4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (c000000000d2bf2c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (c000000000dfb3b4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (c000000000e06b94)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (c000000000e9e0a8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/riscv/kernel/ptrace.c (ffffffe0000b645e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
```
```
In kernel/capability.c (ffffffe0000cb3f0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
```
```
In kernel/ptrace.c (ffffffe0000cc3c8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In kernel/time/timekeeping.c (ffffffe000131a8c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffe000145334)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/audit.c (ffffffe000160ae6)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffe000160f56)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (ffffffe000166528)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffe0001669ee)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffe000167268)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffe0001686de)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:trim_marked
```
```
In mm/mmap.c (ffffffe00020e4f2)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffe0002548e2)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffe00025ee02)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/pipe.c (ffffffe000260a60)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (ffffffe000264726)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:__se_sys_fsetxattr
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a15d4)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffe0002ee87a)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffe000380022)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffe000382b1c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffe000385688)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffe000386886)
Location: include/linux/audit.h:287
Inline: True
```
```
In ipc/sem.c (ffffffe000389e96)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:__se_sys_semctl
```
```
In ipc/shm.c (ffffffe00038b600)
Location: include/linux/audit.h:287
Inline: True
```
```
In ipc/mqueue.c (ffffffe00038cec4)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffe0003a7dac)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae756)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffe0003bd222)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffe0003c9eea)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffe0003f51d6)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f8878)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffe0003f8bb6)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffe0003fd330)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffe000539dfc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffe00073afd2)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffe00075f23e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082acba)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffe000831c96)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffe0008971b0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/x86/entry/common.c (ffffffff810041c5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff810a6d1f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810a820e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff81133c00)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff8114dc48)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8116fa4e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8116ff05)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (ffffffff81176705)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81176cd0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff811775be)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff811782a6)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:trim_marked
```
```
In mm/mmap.c (ffffffff812621ab)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812d1f1b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812de62f)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/pipe.c (ffffffff812e0ad4)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (ffffffff812e513a)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff813855ff)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142a19e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8142c31f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff8142fc76)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8143115f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8143390a)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81437872)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8143a4b5)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffff81458c9e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff81460af9)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8146fe07)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff8147dabc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff814ad00b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff814b1087)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b137f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b5dd5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff81655fd5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff818b0c62)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff818d9b35)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff8192a29e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd46c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5526)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81a33900)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/x86/entry/common.c (ffffffff81002695)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff810956ff)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff81096bce)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff81126660)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff81140ef8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff81162bee)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff811630a5)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (ffffffff811698a5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81169e70)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8116a75e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff8116b446)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:trim_marked
```
```
In mm/mmap.c (ffffffff812545cb)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812c2b9b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812cf95f)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/pipe.c (ffffffff812d1714)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (ffffffff812d5d7a)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff8137608f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8141ac1e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8141cd9f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff814206f6)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff81421bdf)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142438a)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff814282e2)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8142af25)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffff814496ce)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff81451529)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81460827)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff8146e4dc)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff8149da2b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff814a1aa7)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff814a1d9f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814a67f5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff81636365)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff8186abb2)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff81893975)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff818e404e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197a25c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81982316)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff819f0520)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/x86/entry/common.c (ffffffff81004185)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff810a627f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810a776e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff81131920)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff8114baf8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8116d81e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8116dcd5)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (ffffffff811744d5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81174aa0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff8117538e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff81176076)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:trim_marked
```
```
In mm/mmap.c (ffffffff8125ff4b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812cfd2b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812dc43f)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/pipe.c (ffffffff812de8e4)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (ffffffff812e2f4a)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff813830cf)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142633e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814284bf)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff8142be16)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8142d2ff)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff8142faaa)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff81433a12)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff81436655)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffff81454d3e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff8145cb99)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff8146bea7)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff81479b5c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff814a90ab)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff814ad117)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ad40f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814b1e65)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff81684395)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff81901c62)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff8192ab65)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff8197b42e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a27eec)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2ffa6)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81a9f7b0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
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
In arch/x86/entry/common.c (ffffffff810042a5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In kernel/capability.c (ffffffff810ae35f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
```
In kernel/ptrace.c (ffffffff810af88e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/time/timekeeping.c (ffffffff8113e340)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/module.c (ffffffff811587e8)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
```
In kernel/audit.c (ffffffff8117b019)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (ffffffff8117b4c5)
Location: include/linux/audit.h:287
Inline: True
```
```
In kernel/auditsc.c (ffffffff81181db5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
```
```
In kernel/audit_watch.c (ffffffff81182380)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (ffffffff81182c6e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (ffffffff81183952)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - kernel/audit_tree.c:trim_marked
```
```
In mm/mmap.c (ffffffff8126f91b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In fs/open.c (ffffffff812e0b3b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/open.c:ksys_fchown
  - fs/open.c:ksys_fchmod
```
```
In fs/exec.c (ffffffff812ed1d6)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/pipe.c (ffffffff812ef854)
Location: include/linux/audit.h:287
Inline: True
```
```
In fs/namei.c (ffffffff812f2e88)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/devpts/inode.c (ffffffff81396bef)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8143d1fe)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8143f37f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In ipc/util.c (ffffffff81442e36)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
```
```
In ipc/msg.c (ffffffff8144365b)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/msg.c:msgctl_stat
```
```
In ipc/sem.c (ffffffff814453e9)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/sem.c:semctl_stat
```
```
In ipc/shm.c (ffffffff8144a16d)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
```
```
In ipc/mqueue.c (ffffffff8144cdf9)
Location: include/linux/audit.h:287
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
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
```
In security/selinux/hooks.c (ffffffff8146f6fb)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
```
In security/selinux/selinuxfs.c (ffffffff81474339)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (ffffffff81483656)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:compute_sid_handle_invalid_context
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/lsm_audit.c (ffffffff8149160c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/integrity/integrity_audit.c (ffffffff814c1abb)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/ima/ima_api.c (ffffffff814c5b67)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (ffffffff814c5e5f)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In security/integrity/evm/evm_secfs.c (ffffffff814ca8e5)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In drivers/tty/tty_audit.c (ffffffff8169e9a7)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In net/socket.c (ffffffff81922c02)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__sys_socketpair
  - net/socket.c:move_addr_to_user
```
```
In net/core/dev.c (ffffffff8194c235)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/core/dev.c:__dev_set_promiscuity
```
```
In net/compat.c (ffffffff8199d97e)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3351c)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b926)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/netlabel/netlabel_user.c (ffffffff81aab9b0)
Location: include/linux/audit.h:287
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
</details>
</li>
</ul>

## Differences
