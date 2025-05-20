# Function: <code>selinux_cred</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a39b5)
Location: security/selinux/include/objsec.h:156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_secureexec
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:superblock_has_perm
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
```
In security/selinux/xfrm.c (ffffffff813c01f4)
Location: security/selinux/include/objsec.h:156
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff813c97b5)
Location: security/selinux/include/objsec.h:160
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:superblock_has_perm
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
```
In security/selinux/xfrm.c (ffffffff813e63a0)
Location: security/selinux/include/objsec.h:160
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff828cde60)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
```
In security/selinux/xfrm.c (ffffffff814335d1)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff828e78b8)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
```
In security/selinux/xfrm.c (ffffffff81460fee)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff828f03a4)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8146677f)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff8147ad9e)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff82d055b2)
Location: security/selinux/include/objsec.h:152
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff814ba36d)
Location: security/selinux/include/objsec.h:152
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff814d08e5)
Location: security/selinux/include/objsec.h:152
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff82ff298f)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff814d7d4d)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff814eddf5)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff831fd36b)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff814de6bd)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff814f4b65)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff832e4570)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_lockdown
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff815375bd)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff8154f545)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff8349b152)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_current_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff815ce9b4)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff815e8815)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff83ed1f98)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_task_prctl
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_current_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8167c494)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff81698035)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff836f703d)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_task_prctl
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_current_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff816b46d9)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff816d0515)
Location: security/selinux/include/objsec.h:151
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff8392a3ad)
Location: security/selinux/include/objsec.h:152
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_perf_event_write
  - security/selinux/hooks.c:selinux_perf_event_read
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_perf_event_open
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_watch_key
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_lsm_getattr
  - security/selinux/hooks.c:selinux_lsm_getattr
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getlsmblob_obj
  - security/selinux/hooks.c:selinux_current_getlsmblob_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getlsmblob
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committing_creds
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff816f1239)
Location: security/selinux/include/objsec.h:152
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff8170cb35)
Location: security/selinux/include/objsec.h:152
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_state_delete
  - security/selinux/xfrm.c:selinux_xfrm_policy_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffff80001146a364)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffff800010554a9c)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffff80001056b434)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (c1542f48)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:ptrace_parent_sid
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:may_context_mount_sb_relabel
```
```
In security/selinux/selinuxfs.c (c0709c0c)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (c071ef28)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (c00000000139889c)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:may_context_mount_sb_relabel
```
```
In security/selinux/selinuxfs.c (c0000000006b1b64)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (c0000000006cf3d8)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffe0000253fc)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:may_context_mount_sb_relabel
```
```
In security/selinux/selinuxfs.c (ffffffe0003acf30)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffe0003c02b2)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff828d9258)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8145ed5f)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff8147337e)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff828d1974)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8144f78f)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff81463d9e)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff828ebfd8)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8145adff)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff8146f41e)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
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
In security/selinux/hooks.c (ffffffff828f13ee)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_key_alloc
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_transfer
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_cred_prepare
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:ptrace_parent_sid
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8147259f)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/xfrm.c (ffffffff81486c8e)
Location: security/selinux/include/objsec.h:148
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
</details>
</li>
</ul>

## Differences
