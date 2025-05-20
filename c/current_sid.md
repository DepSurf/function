# Function: <code>current_sid</code>

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
In security/selinux/hooks.c (ffffffff813418ad)
Location: security/selinux/hooks.c:216
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:current_has_perm
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
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
In security/selinux/hooks.c (ffffffff81377749)
Location: security/selinux/hooks.c:216
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:current_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
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
In security/selinux/hooks.c (ffffffff8138e159)
Location: security/selinux/hooks.c:216
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:current_has_perm
  - security/selinux/hooks.c:selinux_set_mnt_opts
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
In security/selinux/hooks.c (ffffffff813a9d78)
Location: security/selinux/include/objsec.h:47
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff813ad5cd)
Location: security/selinux/include/objsec.h:47
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
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
In security/selinux/hooks.c (ffffffff813cff88)
Location: security/selinux/include/objsec.h:47
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff813d368d)
Location: security/selinux/include/objsec.h:47
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
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
In security/selinux/hooks.c (ffffffff813fc7d8)
Location: security/selinux/include/objsec.h:44
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8140320b)
Location: security/selinux/include/objsec.h:44
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
In security/selinux/hooks.c (ffffffff814161e8)
Location: security/selinux/include/objsec.h:46
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8141ed1b)
Location: security/selinux/include/objsec.h:46
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
In security/selinux/hooks.c (ffffffff81443c48)
Location: security/selinux/include/objsec.h:43
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8144c97b)
Location: security/selinux/include/objsec.h:43
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
In security/selinux/hooks.c (ffffffff8145d7b8)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff81466776)
Location: security/selinux/include/objsec.h:181
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
In security/selinux/hooks.c (ffffffff814af195)
Location: security/selinux/include/objsec.h:185
Inline: True
Inline callers:
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
  - security/selinux/hooks.c:selinux_setprocattr
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
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff814ba364)
Location: security/selinux/include/objsec.h:185
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
In security/selinux/hooks.c (ffffffff814ccc35)
Location: security/selinux/include/objsec.h:184
Inline: True
Inline callers:
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
  - security/selinux/hooks.c:selinux_setprocattr
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
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff814d7d44)
Location: security/selinux/include/objsec.h:184
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
In security/selinux/hooks.c (ffffffff814d3255)
Location: security/selinux/include/objsec.h:184
Inline: True
Inline callers:
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
  - security/selinux/hooks.c:selinux_setprocattr
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
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff814de6b4)
Location: security/selinux/include/objsec.h:184
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
In security/selinux/hooks.c (ffffffff8152bf15)
Location: security/selinux/include/objsec.h:184
Inline: True
Inline callers:
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
  - security/selinux/hooks.c:selinux_setprocattr
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
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff815375b4)
Location: security/selinux/include/objsec.h:184
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
In security/selinux/hooks.c (ffffffff815c1de5)
Location: security/selinux/include/objsec.h:184
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
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
  - security/selinux/hooks.c:selinux_setprocattr
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
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_current_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff815ce9ab)
Location: security/selinux/include/objsec.h:184
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
In security/selinux/hooks.c (ffffffff8166e4d5)
Location: security/selinux/include/objsec.h:184
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
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
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_task_prctl
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
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_current_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8167c48b)
Location: security/selinux/include/objsec.h:184
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
In security/selinux/hooks.c (ffffffff816a6ba0)
Location: security/selinux/include/objsec.h:184
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
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
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_task_prctl
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
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_current_getsecid_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff816b46d0)
Location: security/selinux/include/objsec.h:184
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
In security/selinux/hooks.c (ffffffff816e36c3)
Location: security/selinux/include/objsec.h:185
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_uring_sqpoll
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
  - security/selinux/hooks.c:selinux_lsm_setattr
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
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_userns_create
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_current_getlsmblob_subj
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_syslog
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_rename
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff816f1230)
Location: security/selinux/include/objsec.h:185
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
In security/selinux/hooks.c (ffff80001054a6dc)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffff800010554a9c)
Location: security/selinux/include/objsec.h:181
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
In security/selinux/hooks.c (c070054c)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (c0709c0c)
Location: security/selinux/include/objsec.h:181
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
In security/selinux/hooks.c (c0000000006af0f8)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (c0000000006b1b64)
Location: security/selinux/include/objsec.h:181
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
In security/selinux/hooks.c (ffffffe0003a5232)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffe0003acf2a)
Location: security/selinux/include/objsec.h:181
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
In security/selinux/hooks.c (ffffffff81455d98)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8145ed56)
Location: security/selinux/include/objsec.h:181
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
In security/selinux/hooks.c (ffffffff814467d8)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8144f786)
Location: security/selinux/include/objsec.h:181
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
In security/selinux/hooks.c (ffffffff81451e38)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff8145adf6)
Location: security/selinux/include/objsec.h:181
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
In security/selinux/hooks.c (ffffffff81468bc8)
Location: security/selinux/include/objsec.h:181
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (ffffffff81472596)
Location: security/selinux/include/objsec.h:181
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
</details>
</li>
</ul>

## Differences
