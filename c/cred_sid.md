# Function: <code>cred_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81341910)
Location: security/selinux/hooks.c:192
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:current_has_perm
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137981b)
Location: security/selinux/hooks.c:192
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:current_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8139028a)
Location: security/selinux/hooks.c:192
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setotherxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:current_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a99ac)
Location: security/selinux/hooks.c:199
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_bprm_set_creds
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
  - security/selinux/hooks.c:superblock_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
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
In security/selinux/hooks.c (ffffffff813cf948)
Location: security/selinux/hooks.c:200
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_bprm_set_creds
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
  - security/selinux/hooks.c:superblock_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fc5dc)
Location: security/selinux/hooks.c:227
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81418d23)
Location: security/selinux/hooks.c:217
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81446a6d)
Location: security/selinux/hooks.c:218
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81460605)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814af45f)
Location: security/selinux/hooks.c:223
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cceff)
Location: security/selinux/hooks.c:224
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d34ff)
Location: security/selinux/hooks.c:224
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152c1bf)
Location: security/selinux/hooks.c:224
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c1e85)
Location: security/selinux/hooks.c:223
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8166e595)
Location: security/selinux/hooks.c:225
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a6c55)
Location: security/selinux/hooks.c:221
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsecid_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e3775)
Location: security/selinux/hooks.c:224
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_override_creds
  - security/selinux/hooks.c:selinux_key_permission
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getlsmblob_obj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_cred_getlsmblob
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_creds_for_exec
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capset
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transfer_binder
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054dd94)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06ff070)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:ptrace_parent_sid
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006ac838)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a7d5c)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81458be5)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81449615)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81454c85)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814699d9)
Location: security/selinux/hooks.c:220
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_msg_queue_msgrcv
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
  - security/selinux/hooks.c:selinux_cred_getsecid
  - security/selinux/hooks.c:selinux_file_send_sigiotask
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:ptrace_parent_sid
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
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:file_has_perm
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:cred_has_capability
```
</details>
</li>
</ul>

## Differences
